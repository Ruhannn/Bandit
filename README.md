# OverTheWire Bandit Walkthrough

This repo contains my solutions and commands for Bandit wargame levels.

---

## Level 1
**Password:** ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If  
**Command:**  
```bash
cat
````

## Level 2

**Password:** 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
**Command:**

```bash
cat <
```

## Level 3

**Password:** MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
**Command:**

```bash
cat "./"
```

## Level 4

**Password:** 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
**Commands:**

```bash
ls -l
file ./*
cat ./file07
```

## Level 5

**Password:** 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
**Commands:**

```bash
find . -type f -size 1033c
cat "./maybehere07/.file2"
```

## Level 6

**Password:** HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
**Commands:**

```bash
find / -user bandit7 -group bandit6 -size 33c
cat /var/lib/dpkg/info/bandit7.password
```

## Level 7

**Password:** morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
**Command:**

```bash
cat data.txt | grep 'millionth'
```

## Level 8

**Password:** dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
**Command:**

```bash
sort data.txt | uniq -u
```

## Level 9

**Password:** 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
**Command:**

```bash
strings data.txt
```

## Level 10

**Password:** FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
**Command:**

```bash
base64 -d data.txt
```

## Level 11

**Password:** dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
**Command:**

```bash
tr 'A-Za-z' 'N-ZA-Mn-za-m' < data.txt  # ROT13
```

## Level 12

**Password:** 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
**Commands:**

```bash
xxd -r data.txt > data
bzip2 -d data.bz2
gzip -d data.gz
tar xf data.tar
```

## Level 13

**Password:** FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn




[website](https://overthewire.org/wargames/bandit/bandit14.html)
