# Level 0
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
#bandit0
```
# Level 1
```bash
ls
cat readme
```
# Level 2
```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220 
#ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
ls -la
cat ./-
```
# Level 3
```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220 
#263JGJPfgU6LtdEvgfWU1XP5yac29mFx
cat ./--spaces\ in\ this\ filename--
```
# Level 4
```bash
ssh bandit3@bandit.labs.overthewire.org -p 2220
#MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
cd inhere
ls -la
cat ./...Hiding-From-You
```
# Level 5
```bash
ssh bandit4@bandit.labs.overthewire.org -p 2220
#2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
cd inhere
file ./*
cat ./-file07
```
# Level 6
```bash
ssh bandit5@bandit.labs.overthewire.org -p 2220
#4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
cd inhere
find . -type f -size 1033c ! -executable
```
# Level 7
```bash
ssh bandit6@bandit.labs.overthewire.org -p 2220
#HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
find / -size 33c -group bandit6 -user bandit7 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password
```
# Level 8
```bash
ssh bandit7@bandit.labs.overthewire.org -p 2220
#morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
grep "millionth" data.txt
dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
```
# Level 9
```bash
ssh bandit8@bandit.labs.overthewire.org -p 2220
#dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
sort data.txt | uniq -u
```
# Level 10
```bash
ssh bandit9@bandit.labs.overthewire.org -p 2220
#4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
strings data.txt | grep '==='
```
# Level 11
```bash
ssh bandit10@bandit.labs.overthewire.org -p 2220
#FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
cat data.txt | base64 -d
```
# Level 12
```bash
ssh bandit11@bandit.labs.overthewire.org -p 2220
#dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
cat data.txt | tr 'a-zA-Z' 'n-za-mN-ZA-M'
```
# Level 13
```bash
ssh bandit12@bandit.labs.overthewire.org -p 2220
#7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
xxd -r data.txt > binario.bin
file binario.bin
mv binario.bin binario.gz
gunzip binario.gz
file binario
binario binario.bz2
bzip2 -d binario.bz2
file binario
mv binario binario.gz
gunzip binario.gz
file binario
tar -xvf binario.tar
file data5.bin
mv data5.bin binario.tar
tar -xvf binario.tar
file data6.bin
mv data6.bin binario.tar
tar -xvf binario.tar
file data8.bin
mv data8.bin binario.gz
gunzip binario.gz
file binario
cat binario
```
# Level 14
```bash
ssh bandit13@bandit.labs.overthewire.org -p 2220
#FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
scp -P 2220 bandit13@bandit.labs.overthewire.org:/home/bandit13/sshkey.private .
```