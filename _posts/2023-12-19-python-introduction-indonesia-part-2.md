---
layout: post
title:  "Python Introduction - Indonesia - Part 2"
tags: [python, coding, tutorial]
updated: "2023-11-28"
---
# Previous Part
[Part 1]({% link _posts/2023-11-22-python-tutorial.md %})

## Exercises
Dalam post ini, saya akan kompilasikan beberapa coding exercises untuk belajar logic-logic sederhana

### 1. if else

<p>Question: </p>
<p>Jika ada dua bilangan bulat, kembalikan nilai perkalian keduanya jika hasilnya sama dengan atau lebih rendah dari 1000.</p>
<p>Selain itu, kembalikan hasil penjumlahan mereka</p>

<p>Contoh hasil:</p>

```
# Case 1
a = 20
b = 30

>> 600
```

```
# Case 2
a = 40
b = 30

>> 70
```

### 2. penjumlahan berturut
<p>Question: </p>
<p>Buatlah sebuah program yang akan terus-menerus beriterasi di 10 bilangan pertama (dimulai dari 0), dan di setiap iterasi, `print` hasil angka iterasi dengan angka iterasi sebelumnya</p>

<p>Contoh hasil: </p>

```
# Case 1

batas = 10

>> 0 + 0 = 0 # <- kita mulai dari 0, tidak dari -1
>> 1 + 0 = 1
>> 2 + 1 = 3
>> 3 + 2 = 5
>> 4 + 3 = 7
>> 5 + 4 = 9
>> 6 + 5 = 11
>> 7 + 6 = 13
>> 8 + 7 = 15
>> 9 + 8 = 17
```

### 3. odd/even number logic

<p>Question: </p>
<p>Print karakter dalam sebuah kata, yang indeks karakternya adalah bilangan ganjil (0 dianggap bilangan genap)</p>

<p>Contoh: </p>

```
# Case 1

kata = "luqman"

>> u
>> m
>> n
```


## CRUD

Nah, jadi kita sudah belajar banyak mengenai python, mulai dari syntax, konsep-konsep dasar, dan juga sedikit algoritma.

Sekarang kita bisa mulai mengaplikasikan apa yang telah kita pelajari, untuk membuat sebuah aplikasi kita sendiri!

Untuk itu, kita kenali konsep *CRUD*, _Create Read Update Delete_. CRUD secara esensial, adalah fundamental cara bekerja sebuah aplikasi.

Katakan kita membuka aplikasi marketplace untuk berjualan. Pertama kita pasti diminta untuk membuat sebuah akun. Lalu setelah itu, kita akan login, dan bisa memasukkan data barang yang akan dijual. Tapi ternyata setelah memasukkan data barang, ada data yang salah, misalkan jumlah stok atau deskripsi yang salah, sehingga kita melakukan perubahan. Dan setelah stok habis, kita berhenti berjualan barang tersebut, sehingga kita menghapus listing barang itu dari marketplace.

## Changelog
### 2023-12-19
- added 3 simple exercises. Todo: example implementation
- mula8 cerita singkat untuk CRUD