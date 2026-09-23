# OverTheWire : Level 7 - 8

## Objectives
Mencari Password yang terdapat di dalam file data.txt dan berada di sebelah kata "millionth". Karena di dalam file itu terdapat banyak tulisan, maka kita menggunakan command "grep" untuk mencari kata "millionth"

## Purpose
Mempelajari dan menggunakan command "grep" untuk mencari suatu string atau kata dalam suatu file

## Solutions
```bash
# Login ke bandit7
ssh bandit7@bandit.labs.overthewire.org -p 2220
```

```bash
# Mencari String yang mengandung millionth
grep "millionth" data.txt
```

![Bandit Level 7 - 8](sslevel7-8,png)


**Penjelasan :** command "grep" berfungsi untuk mencari suatu kata atau string dalam sebuah file atau data

**Password :** VR1ljMayciFxbnUokuQmJFw6QC9VKtub

