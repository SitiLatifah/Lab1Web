# Lab1Web
**Nama	   	: Siti Latifah** <br>
**Nim	  	  : 312010321** <br>
**Kelas	  	: TI.20.A2** <br>
**Matkul	  : Pemrograman Web** <br>

# Soal
![1](https://user-images.githubusercontent.com/73010098/157592162-105797da-bf71-4226-be9c-0acd5e41f609.png)

# BELAJAR DASAR HTML

1. Membuka Aplikasi (Sublime Text)

![2](https://user-images.githubusercontent.com/73010098/157594644-a71537ba-69e1-40ec-98d5-1f42521ffbb7.png)

2. Membuat File Baru

![3](https://user-images.githubusercontent.com/73010098/157594670-fa8fa00d-2b58-4475-ab1e-a75351ecaa0f.png)

3. Save File Dengan format HTML

![4](https://user-images.githubusercontent.com/73010098/157594731-918e5bf6-0900-4d00-8855-0a8d9f799473.png)

4. Ketik Syntax HTML

``` html
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title></title>
</head>
<body>
```

5. Mengubah Nama Title

``` html
<title>Tag HTML Dasar</title>
```
#### OUTPUT

![6 (2)](https://user-images.githubusercontent.com/73010098/157596180-a99e8ca1-baf6-4806-a9d6-7d4d207a0af9.jpg)

6. Menambahkan Tag Navigasi

``` html
<a href="index.html">Home</a>
<a href="halaman1.html">Halaman 1</a>
<a href="https://github.com/SitiLatifah">Link github</a>
```
#### OUTPUT

![8](https://user-images.githubusercontent.com/73010098/157596238-00ee80cb-230d-42c6-8490-f562c5a77387.png)


7. Membuat Judul Paragraf Pertama Menggunakan Tag H1 dan align center (Rata tengah)

``` html
<!-- Judul Paragraf Pertama -->
<h1 align="center">Belajar Dasar HTML</h1>
```
#### OUTPUT

![10](https://user-images.githubusercontent.com/73010098/157596295-a3a056c1-6c6c-4850-8bb0-f9f036ce840d.png)


8. Membuat Paragraf pertama menggunakan tag align center dan memformat teks menggunakan tag font color, bold, dan underline

``` html
<!-- Paragraf pertama -->
<p align="center">Kami sedang belajar<font color="red"> HTML dasar</font>, pada matakuliah <b>pemrograman web</b> di prodi Teknik Informatika<br>
<u>Universitas Pelita Bangsa</u>. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana<br>
dalam rangka mengenal tag-tag dasar HTML.</p>
```
#### OUTPUT

![11](https://user-images.githubusercontent.com/73010098/157596663-3d5d2055-fdc0-489b-a7a1-430ed3f298f5.png)


9. Membuat judul paragraf kedua menggunakan tag H2 dan Align left (rata Kiri)

``` html
<!-- Judul Paragraf kedua -->
<h2 align="left">Tag Dasar HTML</h2>
```
#### OUTPUT

![13](https://user-images.githubusercontent.com/73010098/157596732-674241e7-d1c9-4f9e-a20b-a223d31e625b.png)

10. Membuat Paragraf Kedua dengan Align Left

``` html
<!-- paragraf Kedua -->
<p align="left"> Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung<br>
sehingga menjadi satu kesatuan. paragraf dibuat dengan menggunakan tag dasar HTML.</p>
```
#### OUTPUT

![15](https://user-images.githubusercontent.com/73010098/157596507-ec979cfb-c62c-42c1-a1dc-41585c685545.png)


11. Menyisipkan Atau menambahkan gambar

``` html
<!-- Menambahkan Gambar -->
<h2 align="center">Menambahkan Gambar</h2>
<center>
    <img src="picture1.png" alt="logo_upb">
```
#### OUTPUT

![17](https://user-images.githubusercontent.com/73010098/157596547-4c6f6db9-c353-4a50-abaa-368c84860cba.png)


## JAWAB PERTANYAAN BERIKUT

1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah 
error ketika terjadi kesalahan penulisan tag?
Jawab   : Pada saat menggunakan kode tidak terdapat error jika menggunakan kode dengan benar, jika terjadi typo ataupun kurangnya huruf atau tanda maka terjadi error pada kode yang dibuat.

2. Apa perbedaan dari tag **p** dengan tag **br**, berikan penjelasannya!
Jawab   : Tag  **p** Tag ini berfungsi untuk memberi perintah paragraf baru pada halaman html, biasa digunakan untuk membuat sebuah paragraph pada HTML.
          Tag **br** dituliskan pada kerangka html untuk memberikan perintah "break line", artinya meng intruksikan baris baru.
          
3. Apa perbedaan atribut title dan alt pada tag **img**, berikan penjelasannya!
Jawab   : a.  Alt text atau text alternatif adalah atribut yang ditambahkan ke tag gambar dalam HTML. Teks ini muncul di dalam wadah gambar ketika gambar tidak dapat                ditampilkan. Ini membantu mesin pencari memahami apa isi dari gambar tersebut. Text alternatif juga sangat membantu dalam kasus gambar yang tidak                      ditemukan pada halaman atau gambar rusak.
          b. Title image adalah atribut lain yang dapat ditambahkan ke tag gambar dalam HTML. Title image ini digunakan untuk memberikan judul untuk gambar Anda. Text              yang Anda masukkan di dalam tag judul tidak akan ditampilkan kepada pengguna ketika gambar tidak dapat ditampilkan. Sebaliknya, tag judul gambar ini                    ditampilkan saat Anda menyorot gambar dengan mouse.
   
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar 
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
Jawab   : Lebih baik diisi karena pembuat program dapat mengatur ukuran gambar secara panjang dan lebar gambar, dan tidak semua gambar pada html mempunyai ukuran yang           langsung ideal untuk ditampilkan terkadang gambar terlalu besar atau terlalu kecil, maka dari itu lebih baik menggunakan height dan weight pada gambar/logo             di HTML.
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, 
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
Jawab   : a. 
            **a href="link" target="_self">penamaan link/a** 
            untuk membuka link di frame link itu berada. ini merupakan setelan dasar link jika pada elemen link tidak diberi atribut target 
         b. 
            **a href="link" target="_blank">penamaan link/a** 
            untuk membuka link di tab baru 
         c. 
            **a href="link" target="_parent">penamaan link/a** 
            untuk membuka link di frame yang satu tingkat di atas frame link tersebut berada. secara simple-nya begini : jika di website(1) di dalamnya ada website(2)             lalu di website(2) ini ada link dan kita klik, maka link akan terbuka di website(1) 
        d.
            **a href="link" target="_top">penamaan link/a** 
            untuk membuka link di frame paling atas (paling luar). secara simpel-nya : jika di website(1) di dalamnya ada website(2) lalu di website(2) di dalamnya ada             website (3) lalu di website (3) ini ada link dan kita klik, maka link akan terbuka di website(1)



