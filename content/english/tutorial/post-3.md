---

title: "Cara Memunculkan File Tersembunyi di Flashdisk Karena Virus"
meta_title: ""
description: "File Tersembunyi di Flashdisk"
date: 2022-04-04T05:00:00Z
image: "/images/command-atribute.png"
categories: ["Tips"]
author: "John Doe"
tags: ["Virus", "Tutorial"]
draft: false
---

Cara Memunculkan File Tersembunyi di Flashdisk Karena Virus – Keberadaan virus di komputer memang sangat sulit dideteksi / diketahui, karena virus mempunyai kemampuan untuk bersembunyi, menggandakan diri & menyebar ke dalam komputer tanpa diketaui oleh pengguna komputer tersebut.

silahkan lakukan langkah berikut :

## Melihat File/Folder Yang Tersembunyi

1. Buka "File Explorer" Windows> Buka "Tools"> Opsi "Folder"> Buka Tab "View"> Centang "Show hidden files, folders, and drives". Terakhir, klik "Apply". Cara ini akan memastikan bahwa file dan folder tidak dalam mode tersembunyi.

{{< image src="images/show-hidden-files-with cmd.png" caption="" alt="alter-text" height="" width="" position="center" command="fill" option="q100" class="img-fluid" title="image title"  webp="true" zoomable="true" >}}

2. Buka menu “Run”. ini bisa dilakukan dengan menekan tombol “Windows + R” pada keyboard. Setelah itu ketik “CMD” lalu tekan enter. Akan muncul sebuah jendela cmd berwarna hitam.
   
3. Pada jendela cmd tersebut Ketik drive letter partision flash disk. Misalnya “G:” (tanpa tanda kutip) lalu tekan enter.
    
4. Perintah CMD untuk memunculkan file super hidden oleh virusKetik perintah “attrib -s -h -r *.* /s /d” (tanpa tanda kutip) & enter. Tunggu beberapa saat hingga drive letter partition yang anda ketik sebelumnya muncul kembali pada baris paling bawah. Lihat gambar di bawah ini.

{{< image src="images/command-atribute.png" caption="" alt="alter-text" height="" width="" position="center" command="fill" option="q100" class="img-fluid" title="image title"  webp="true" zoomable="true" >}}

5. Buka flashdisk kemudian periksa file-folder yang ada di dalam flashdisk anda.

## Semoga Tips Ini bisa membantu 🙏.
