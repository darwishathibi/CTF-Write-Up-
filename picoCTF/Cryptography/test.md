## Introduction
-**Event:** Pico CTF
-**Category:** Cryptography
-**Difficulity:** Easy

## Description
In this challenge, the author asked us to download a file and decode it. The hint is given which is: Engaging in various decoding processes is of utmost importance 
![Screenshot_2024-09-25_14-55-24](https://github.com/user-attachments/assets/a1b308f5-2dc1-49d8-9d77-2d012a6df4af)

## Methode
From the hints, it shows that maybe the string inside the file fiven is multiple encoding process of base64 or something else.
![Screenshot_2024-09-25_04-55-03](https://github.com/user-attachments/assets/51067254-4ff7-498b-8c8d-18f46ddc080e)

Based on the string it seems like encode using base64. So I try to use dCode and decode it.
![Screenshot_2024-09-25_04-56-25](https://github.com/user-attachments/assets/3e02d39c-d15e-4fff-b758-e396801d2003)

After decode the string, it seems like that is not like the flag and I juts copy paste and decode it , but it shows weird string.
![Screenshot_2024-09-25_04-56-58](https://github.com/user-attachments/assets/6bf2dcf3-877c-41e0-877e-6764ba83e52c)

Then, I realize the a string between quotation mark. I copy it and try decode it, and found something promising.
![Screenshot_2024-09-25_04-57-26](https://github.com/user-attachments/assets/3957cc40-ae2b-457e-94df-0568bb3636bd)

I asked chatgpt, "how much the rotation 'wpjvJAM' to 'picoCTF'?". the answer is rot 19.
![Screenshot_2024-09-25_05-03-10](https://github.com/user-attachments/assets/dd249df1-ddad-4c47-913a-caf8d87d4612)

## Flag
picoCTF{caesar_d3cr9pt3d_86de32d2}
