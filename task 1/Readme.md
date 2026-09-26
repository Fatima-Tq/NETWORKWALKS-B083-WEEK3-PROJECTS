\# Password Cracking with John the Ripper (JTR)



\## 📌 Overview



This lab focuses on using \*\*John the Ripper (JTR)\*\* and \*\*Johnny GUI\*\* to recover the password of a protected PDF file.



John the Ripper is a password security testing tool that supports different password hash formats. Johnny is its graphical interface, which makes the process easier for beginners.



The main purpose of this task is to understand how password hashes can be used in password recovery and why strong passwords are important in cybersecurity.



\## 🎯 Objectives



\* Understand the basic working of John the Ripper.

\* Learn about the Johnny graphical interface.

\* Extract the hash of a password-protected PDF.

\* Save the hash in a text file.

\* Use Johnny to perform a password recovery attack.

\* Open the protected PDF using the recovered password.



\## 🛠️ Tools Used



\* John the Ripper

\* Johnny GUI

\* Windows

\* Notepad

\* Protected PDF file



\## 🔎 Lab Procedure



\### Step 1 — Install John the Ripper



Download John the Ripper from its official website and install it on the Windows system.



\### Step 2 — Install Johnny



Download and install the Johnny GUI, which provides a graphical interface for John the Ripper.



\### Step 3 — Open Johnny



After installation, launch Johnny on the Windows computer.



\### Step 4 — Configure John



Open the settings in Johnny and browse to the `john.exe` file located inside the `run` folder of the John the Ripper installation.



\### Step 5 — Get the PDF Hash



Download the encrypted PDF and use a PDF hash extraction tool to obtain its hash.



The extracted hash should start with:



`$pdf$`



\### Step 6 — Save the Hash



Copy the complete hash and paste it into Notepad. Save the file as a `.txt` file, for example:



`hash1.txt`



If the extracted hash contains extra characters such as `b'`, they should be removed so that the hash starts correctly with `$pdf$`.



\### Step 7 — Load the Hash in Johnny



Open Johnny and select \*\*Open password file\*\*. Browse to the saved `hash1.txt` file and open it.



\### Step 8 — Start the Attack



Select \*\*Start new attack\*\* in Johnny. The tool will try to recover the password from the provided hash.



\### Step 9 — Test the Password



After the password is recovered, open the encrypted PDF and enter the recovered password to verify that the file can be opened.



\## 📚 What I Learned



Through this lab, I learned the basic process of password recovery using John the Ripper and Johnny. I also learned how a password-protected PDF can be converted into a hash and how the hash can be provided to a password-cracking tool.



This activity also helped me understand why strong and less predictable passwords are important for protecting files.



\## ⚠️ Ethical Use



Password-cracking tools should only be used on files, systems, or accounts for which you have permission to perform security testing. This lab was performed for educational and cybersecurity learning purposes.



