# Mesej Rahsia
## Introduction
-**Event:** 3108 CTF
-**Category:** Cryptography

## Decsription
![Screenshot_2024-09-03_11-01-41](https://github.com/user-attachments/assets/bbbe40c7-ca4d-4c1c-970b-bb511bdf0425)
The challlenge ask us to download the .py file and find the flag.

## Methode
Inside the .py file, there are some cipher decoder code and a flag variable. But i realize the sequence of the flag will be in reverse.
![Screenshot_2024-09-03_11-02-59](https://github.com/user-attachments/assets/4b3b7bd8-d8f7-4b38-8a3b-f3ae088c1991)

Then i copy the code and run it in online compiler, but instead of **[::-1]** is change it into **[::1]**.
![Screenshot_2024-09-03_11-02-27](https://github.com/user-attachments/assets/ff69751d-7516-440d-abab-1429a6ec9eea)
![Screenshot_2024-09-03_11-02-39](https://github.com/user-attachments/assets/81242d4f-0420-4c55-b665-18082be7ceeb)

After run it, the flag is there but, need to read carefully. HAHAH!

## Flag
3108{substitute_cipher_text}

