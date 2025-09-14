# Crack The Hash – TryHackMe Room Report

## Objective

The objective of this room is to practice cracking different types of password hashes using tools such as Hashcat along with common wordlists like rockyou.txt.
 
 
## Tools Used
 • Hashcat
 
 • hash-identifier
 
 • Rockyou Wordlist
 
 • Kali Linux

## Approach
 1. Identify the type of hash (MD5, SHA1, SHA256, salted, unsalted, etc.).
 2. Use Hashcat perform dictionary attacks or brute-force attacks.
 3. Apply the rockyou.txt wordlist for commonly used passwords.
 4. In cases of salted hashes, correctly specify the salt during the cracking process.

# Task 1: Simple Hash Cracking

Hash: 48bb6e862e54f2a795ffc4e541caed4d

Answer: easy

<img width="719" height="372" alt="Image" src="https://github.com/Gautam-CyberSec/Crack-the-hash/blob/main/Screenshots/Screenshot%202025-09-14%20190349.png" />

Hash: CBFDAC6008F9CAB4083784CBD1874F76618D2A97

Answer: password123

<img width="719" height="372" alt="Image" src="https://github.com/Gautam-CyberSec/Crack-the-hash/blob/main/Screenshots/Screenshot%202025-09-14%20190440.png" />

Hash: 1C8BFE8F801D79745C4631D09FFF36C82AA37FC4CCE4FC946683D7B336B63032

Answer: letmein

<img width="719" height="372" alt="Image" src="https://github.com/Gautam-CyberSec/Crack-the-hash/blob/main/Screenshots/Screenshot%202025-09-14%20190541.png" />

Hash: $2$12$Dwt1BZj6pcyc3Dy1FWZ5ieeUznr71EeNkJkUlypTsgbX1H68wsRom

Answer: bleh

<img width="719" height="372" alt="Image" src="https://github.com/Gautam-CyberSec/Crack-the-hash/blob/main/Screenshots/Screenshot%202025-09-14%20191541.png" />

Hash: 279412f945939ba78ce0758d3fd83daa

Answer: Eternity22  

<img width="719" height="372" alt="Image" src="https://github.com/Gautam-CyberSec/Crack-the-hash/blob/main/Screenshots/Screenshot%202025-09-14%20193325.png" />

# Task 2: Salted Hash Cracking

Hash: f09edcb1fcefc6dfb23dc3505a882655ff77375ed8aa2d1c13f640fccc2d0c85

Answer: paule

<img width="719" height="372" alt="Image" src="https://github.com/Gautam-CyberSec/Crack-the-hash/blob/main/Screenshots/Screenshot%202025-09-14%20193541.png" />

Hash: 1DFECA0C002AE40B8619ECF94819CC1B

Answer: n63umy8lkf4i

<img width="719" height="372" alt="Image" src="https://github.com/Gautam-CyberSec/Crack-the-hash/blob/main/Screenshots/Screenshot%202025-09-14%20194047.png" />

Hash: $6$aReallyHardSalt$6WKUTqzq.UQQmrm0p/T7MPpMbGNnzXPMAXi4bJMl9be.cfi3/qxIf.hsGpS4
1BqMhSrHVXgMpdjS6xeKZAs02.

Salt: aReallyHardSalt

Answer: waka9

<img width="719" height="372" alt="Image" src="https://github.com/Gautam-CyberSec/Crack-the-hash/blob/main/Screenshots/Screenshot%202025-09-14%20194645.png" />

Hash: e5d8870e5bdd26602cab8dbe07a942c8669e56d6

Salt: tryhackme

Answer 4: 481616481616

<img width="719" height="372" alt="Image" src="https://github.com/Gautam-CyberSec/Crack-the-hash/blob/main/Screenshots/Screenshot%202025-09-14%20194928.png" />
