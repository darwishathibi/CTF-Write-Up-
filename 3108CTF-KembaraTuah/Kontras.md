# Kontras
## Introduction
-**Event:** 3108 CTF
-**Category:** Forensics
-**Difficulity:** Easy

## Description
I'm provided a pdf file that contain the simple history of the state of Perak. Based on the hint given, maybe there is the hidden flag inisde the flag.
![Screenshot_2024-08-29_13-23-52](https://github.com/user-attachments/assets/737e0938-42f0-49c6-86df-f51c686f6db1)

## Methode
There is two methodes I use to solve this challenge:
### Select All the Text
I selecting all the text inside the pdf and try to find something odd. At first, I try to select and copy each of the highlighted words and paste it into .txt file, but it don't show the flag.
![Screenshot_2024-08-29_13-44-36](https://github.com/user-attachments/assets/f8b94e40-7660-4ec1-b72f-ec73a3168f15)

Then, I hit the Ctrl + A, search for any odd inside the file and found one!
![Screenshot_2024-08-29_13-32-30](https://github.com/user-attachments/assets/32bcc79a-ce8d-4e71-8d61-fbb7b0545ef3)

I copy and paste the part that the flag in white colour and wallam, I found it!!
![Screenshot_2024-08-29_13-33-12](https://github.com/user-attachments/assets/a8cd8640-f414-471b-ab16-6f00478a34b2)

### Extract text from pdf
I use a tool called **pdftotext** to extract the text.
![Screenshot_2024-08-29_13-50-53](https://github.com/user-attachments/assets/c452b8c3-ec95-4c04-81c2-ca7f89b22c63)

And immediately grep the flag and found it!!!!!
![Screenshot_2024-08-29_13-51-10](https://github.com/user-attachments/assets/e000184f-47d1-43af-b718-6a0bcb0e01dd)

## Flag
3108{Peghak_Darul_ridzuAn}
