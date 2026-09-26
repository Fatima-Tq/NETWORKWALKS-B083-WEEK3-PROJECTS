# Password Cracking with Networkwalks Tools

## 📌 Overview

This lab demonstrates the basic process of recovering a password from a protected PDF file using online password-security tools provided by Networkwalks.

The task involves two main steps. First, the hash of the encrypted PDF is extracted using the **Hash Calculator**. The extracted hash is then given to the **Password Cracker**, which attempts to find the original password.

## 🎯 Objectives

* Understand the basic concept of password cracking.
* Extract a password hash from a protected PDF.
* Learn how a hash is used during password recovery.
* Use the Networkwalks Hash Calculator.
* Use the Networkwalks Password Cracker.
* Understand the importance of strong passwords.

## 🛠️ Tools Used

* Networkwalks Hash Calculator
* Networkwalks Password Cracker
* Web Browser
* Password-protected PDF

## 🔎 Lab Procedure

### Step 1 — Download the Protected PDF

Download the encrypted PDF file provided for the lab.

### Step 2 — Open Hash Calculator

Open the Networkwalks Hash Calculator in a web browser.

### Step 3 — Upload the PDF

Upload the protected PDF file to the Hash Calculator. The tool extracts the hash from the file.

The generated hash starts with:

```text
$pdf$
```

### Step 4 — Copy the Hash

Copy the complete hash value carefully without missing any part of it.

### Step 5 — Open Password Cracker

Open the Networkwalks Password Cracker in the browser.

### Step 6 — Enter the Hash

Paste the copied PDF hash into the Password Cracker and start the attack.

The tool will try different passwords until it finds a matching password.

### Step 7 — Test the Recovered Password

Open the protected PDF and enter the recovered password to check whether the file opens successfully.

## 📚 What I Learned

This lab helped me understand the basic workflow of password cracking. I learned that a protected PDF can be represented through a hash and that password-cracking tools can use this hash to attempt password recovery.

It also showed why using short or common passwords can make files easier to attack and why strong passwords are important for security.

## ⚠️ Ethical Use

Password-cracking techniques should only be used for educational purposes or on files and systems where proper permission has been given.

This task was performed in a controlled learning environment for cybersecurity learning.
