# WriteUp-CTF

Apa itu Serangan Injeksi SQL?
Serangan SQL Injection (atau SQLi) mengubah kueri SQL, menyuntikkan kode berbahaya dengan mengeksploitasi kerentanan aplikasi. 

Serangan SQLi yang berhasil memungkinkan penyerang untuk memodifikasi informasi database, mengakses data sensitif, menjalankan tugas admin pada database, dan memulihkan file dari sistem. Dalam beberapa kasus, penyerang dapat mengeluarkan perintah ke sistem operasi basis data yang mendasarinya.

1.Basic Injection CTFLearn 🏳️

Payload akan menarik semua data dari database. Ini karena input yang diajukan tidak dibersihkan yang membuat bidang pencarian rentan terhadap injeksi SQL. seorang hacker dapat menarik semua informasi dari database yang termasuk data sensitif.

Secara teori, ini akan membuat permintaan SQL berikut:

SELECT * FROM Users WHERE Name ="" atau ""="" AND Pass ="" atau ""=""
Ini kemudian akan mengembalikan semua pengguna dan kata sandi yang disimpan. Sayangnya, untuk CTF kami, permintaan ini sekali lagi menghasilkan 0 hasil.

![IMG_20220622_214605](https://user-images.githubusercontent.com/107804408/175059039-bf0b01a4-d512-4e3e-adc6-253a2d2de5cb.jpg)

flag : fl4g__giv3r CTFlearn{th4t_is_why_you_n33d_to_sanitiz3_inputs}

Ini adalah bendera kami! Saya menyalin konten data dan mengirimkannya ke CTF Learn dan dengan senang hati menyelesaikan tantangan CTF pertama saya.
