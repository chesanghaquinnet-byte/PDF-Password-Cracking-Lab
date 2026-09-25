# PDF-Password-Cracking-Lab
A cybersecurity lab demonstrating PDF password cracking using John the Ripper and Networkwalks Hash Calculator and Password Cracker.


# Password Cracking Lab

Introduction

Password cracking is the process of recovering a password from a protected file or stored password data.

In cybersecurity, password cracking can be used in authorized security testing to understand how strong or weak passwords are. Weak and common passwords can sometimes be discovered quickly, which shows why strong passwords are important.

In this project, I worked with password-protected PDF files and used two different methods to recover their passwords:

1. John the Ripper (JTR) on Kali Linux
2. Networkwalks Hash Calculator and Password Cracker

The purpose of this lab was to understand how password cracking works and to practice the process in a controlled environment.


## Project Overview

For this lab, I worked with three password-protected PDF files:

* My Locked PDF1.pdf
* My Locked PDF2.pdf
* My Locked PDF3.pdf

I used the first two PDFs to practice password cracking with John the Ripper.

For the third PDF, I used the Networkwalks Hash Calculator and Networkwalks Password Cracker, following the second method provided by my tutor.

The general process was:

was:

```text
Password-Protected PDF
        ↓
Extract PDF Hash
        ↓
Use Password Cracking Tool
        ↓
Recover Password
        ↓
Open the Protected PDF
```

# Tools Used

## John the Ripper

John the Ripper (JTR) is a password-cracking tool that can be used to test password strength by trying different password candidates against a password hash.

### pdf2john

pdf2john was used to extract the password hash from the protected PDF so that John the Ripper could work with it.

## Networkwalks Hash Calculator

The Networkwalks Hash Calculator was used to extract the hash from the protected PDF through a web browser.

## Networkwalks Password Cracker

The Networkwalks Password Cracker was then used to process the extracted PDF hash and recover the password.

## Kali Linux

Kali Linux was the environment used to perform the command-line part of the practical work.


