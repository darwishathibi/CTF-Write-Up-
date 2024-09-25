# Tapping
## Introduction
-**Event:** pico CTF
-**Category:** Cryptography
-**Difficulity:** Medium

## Description
In this challenge, the author gave me a netcat link to connect and decode what inside it.
![Screenshot_2024-09-25_06-11-55](https://github.com/user-attachments/assets/bc427788-bd1c-4435-b17c-a167c4615b38)

## Methode
Based on the hints given, it shows that maybe it is a morse code.
![Screenshot_2024-09-25_06-12-24](https://github.com/user-attachments/assets/06021556-3403-49f4-abeb-f784e2a5924a)

Then, I connect to the netcat, the author gave me a morse code like I expect.
![Screenshot_2024-09-25_06-12-39](https://github.com/user-attachments/assets/d28c1b0b-74fa-4cfc-ac27-49f24a87bd8a)

Then is use dCode to decode the morse code and search the most suitable answer. and found the flag.
![Screenshot_2024-09-25_06-12-56](https://github.com/user-attachments/assets/7d295f5c-bca0-4a3c-a5b5-50ba9b18db75)

## Flag
PICOCTF{M0RS3C0D31SFUN2683824610}
