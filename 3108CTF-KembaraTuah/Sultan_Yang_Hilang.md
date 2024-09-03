# Sultan Yang Hilang
## Introduction
-**Event:** 3108 CTF
-**Category:** Web 

## Description
The challenge ask us to find the lost sultan in order to receive the flag
![Screenshot_2024-09-03_11-11-33](https://github.com/user-attachments/assets/bfae571f-e0f6-43bf-8eab-1146e0efabb2)

## Methode
Inside the web, there is a list of sultan of kelantan from Long Yunus until Sultan Muhammad V
![Screenshot_2024-09-03_11-12-11](https://github.com/user-attachments/assets/abceec40-33ba-471b-b85f-e9c9d7dd3fd1)

So, at first, i just inspect the web and try to find any clue or hint. Suddenly found <script> element inside html page.
![Screenshot_2024-09-03_11-12-34](https://github.com/user-attachments/assets/5a55489d-ac5b-4d0d-ab40-79293a11b7d3)

The script is to display the list of the sultans by fetching from a file.
![Screenshot_2024-09-03_11-12-51](https://github.com/user-attachments/assets/25cd05fe-f21e-41e9-bd61-bf89445a3265)

Then, I seacrh for a list fo sultan kelantan and compare it with the array inside the script.
<Letak ist sultan kelantan sini >

After that, I copy the path from script and paste ii into seacrh bar. Flag is there.
![Screenshot_2024-09-03_11-21-42](https://github.com/user-attachments/assets/d14f3e69-c774-4584-b094-463d8d2f96b9)
![Screenshot_2024-09-03_11-21-54](https://github.com/user-attachments/assets/6e56f720-ecd5-4b1c-a286-691a4bb8cba1)

## Flag
3108{putera_sulong_Sultan_Ahmad}
