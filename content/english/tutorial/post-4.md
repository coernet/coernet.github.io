---
title: "Menonaktifkan Update Windows"
meta_title: ""
description: "window update"
date: 2022-04-04T05:00:00Z
image: "/images/window-update.jpg"
categories: ["Architecture"]
author: "John Doe"
tags: ["window", "tutorial"]
draft: false
---

PEMBARUAN Windows adalah proses di mana sistem operasi Windows diperbarui dengan pemutakhiran terbaru dari Microsoft. Pembaruan ini mungkin mencakup perbaikan keamanan, perbaikan bug, peningkatan fitur, dan lainnya. Pembaruan Windows sangat penting karena membantu menjaga komputer Anda tetap aman dan berfungsi dengan baik.

Biasanya, pembaruan otomatis dapat meningkatkan kinerja dan keamanan komputer atau laptop. Namun, sebagian orang menganggap fitur ini mengganggu.

Masalah ini sering ditemui oleh pengguna Windows 10. Sistem operasi ini memiliki fitur pembaruan otomatis yang sering kali datang secara tak terduga.

<!--more-->

##  Untuk Windows 8, cara menonaktifkan pembaruan Windows adalah sebagai berikut:

    !. Buka File Manager dan klik kanan pada ikon "My PC" di desktop Anda.
    2. Pilih opsi "Manage" dari menu yang muncul.
    3. Di jendela "Computer Management," klik dua kali pada opsi "Service and Applications" untuk mengembangkannya.
    4. Selanjutnya, klik dua kali pada opsi "Services" untuk melihat daftar layanan Windows.
    5. Cari "Windows Update" dalam daftar ini, klik kanan, dan pilih opsi "Properties."
    6. Dalam jendela "Properties," ubah tipe startup dari "automatic (delayed start)" menjadi "disabled."
    7. Klik tombol "Stop" untuk menghentikan layanan pembaruan.
    8. Terakhir, klik "OK" untuk menyimpan pengaturan Anda.
<hr>

## Jika Anda menggunakan Windows 8, berikut adalah cara untuk menonaktifkan pembaruan Windows:

    1. Mulailah dengan masuk ke Control Panel dari menu Start.
    2. Di dalam Control Panel, pilih opsi "System and Security."
    3. Cari "Windows Update" dan klik opsi "Turn automatic updating on or off."
    4. Di jendela berikutnya, Anda akan melihat opsi "Important Updates" dengan dropdown di bawahnya. Klik pada dropdown dan pilih opsi "Never check for updates (not recommended)."
    5. Terakhir, klik "OK" untuk mengonfirmasi perubahan yang telah Anda buat.
<hr>

## Cara pertama untuk menonaktifkan pembaruan Windows 10 adalah sebagai berikut.

    1. Mulailah dengan membuka menu Windows, yang dapat Anda temukan di sudut kiri bawah layar Anda.
    2. Selanjutnya, akses Control Panel melalui menu tersebut.
    3. Di dalam Control Panel, Anda akan menemukan sebuah opsi yang disebut "Administrative Tools." Klik pada opsi ini.
    4. Dalam Administrative Tools, carilah opsi "Services" dan klik untuk membukanya.
    5. Gulir ke bawah dalam daftar layanan hingga Anda menemukan entri yang berhubungan dengan "Windows Update."
    6. Klik dua kali pada entri "Windows Update" ini.
    7. Ketika daftar pembaruan sedang berjalan, Anda akan melihat tombol "Stop" yang memungkinkan Anda untuk menghentikan proses pembaruan.
    8. Selanjutnya, ubah tipe Startup menjadi "Disabled," yang akan menghentikan pembaruan otomatis di masa depan.
    9. Klik tombol "Apply" untuk mengonfirmasi perubahan yang telah Anda buat.
    10. Terakhir, klik "OK" dan lakukan restart pada komputer atau laptop Anda.
<hr>

## Cara kedua untuk menonaktifkan pembaruan Windows 10 adalah sebagai berikut:

    1. Pastikan laptop atau komputer Anda dalam keadaan menyala.
    2. Tekan tombol Windows dan huruf R secara bersamaan untuk membuka jendela "Run."
    3. Di dalam jendela "Run," ketik "Services.msc" dan tekan tombol "OK."
    4. Anda akan dibawa ke daftar layanan Windows. Cari menu "Windows Update" dan klik dua kali untuk membukanya.
    5. Di dalam opsi "Startup Type," pilih "Disable" untuk menonaktifkan pembaruan otomatis.
    6. Klik "Apply" dan kemudian "OK" untuk menyimpan perubahan yang Anda buat.
    7. Terakhir, lakukan restart pada laptop atau komputer Anda untuk memastikan bahwa perubahan ini diterapkan.
<hr>

## Menonaktifkan pembaruan Windows 11 secara sementara.

    1. Tekan tombol Windows + I secara bersamaan atau klik tombol Mulai, lalu pilih Pengaturan untuk membuka Pengaturan Windows.
    2. Di layar Pengaturan Windows, klik pada opsi Pembaruan Windows di panel sebelah kiri untuk mengakses layar Pembaruan Windows. Pada layar ini, Anda dapat memeriksa pembaruan untuk Windows 11, melihat riwayat pembaruan, menjeda pembaruan, bergabung dengan Program Insider Windows, menyesuaikan pengaturan pembaruan lainnya, dan lain sebagainya.
    3. Anda dapat mengklik tombol jeda selama 1 minggu di sebelah opsi jeda pembaruan. Cara ini dapat menghentikan pembaruan Windows 11 selama 7 hari, tetapi setelah itu, Windows akan secara otomatis mengunduh dan menginstal semua pembaruan tertunda ke komputer Anda.
<hr>

## Jika Anda ingin menonaktifkan pembaruan Windows 11 secara permanen, Anda dapat mencoba metode lain di bawah ini.

### Menonaktifkan pembaruan Windows 11 dengan layanan Windows (Windows Services).

    1. Tekan tombol Windows + R, ketik "services.msc" dalam kotak dialog Run, dan tekan Enter untuk membuka Layanan Windows.
    2. Gulir ke bawah dalam daftar layanan dan temukan layanan Pembaruan Windows. Klik dua kali pada layanan Pembaruan Windows untuk membuka jendela properti.
    3. Di bawah tab General, di sebelah opsi Startup type, Anda dapat mengklik ikon drop-down dan memilih opsi Disabled.
    4. Klik Apply dan kemudian klik OK untuk menerapkan perubahan. Dengan cara ini, pembaruan otomatis Windows 11 akan dinonaktifkan secara permanen.
    5. Jika Anda ingin mengaktifkan kembali pembaruan otomatis Windows 11, Anda dapat membuka Layanan Windows lagi untuk mengaktifkan layanan Pembaruan Windows.
<hr>

### Menonaktifkan pembaruan Windows 11 melalui Registry Editor.

    1. Tekan tombol Windows + R, ketik "regedit.exe" dalam kotak dialog Run untuk membuka Registry Editor di Windows 11.
    2. Navigasikan ke jalur berikut di panel kiri: HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate\AU.
    3. Klik kanan pada ruang kosong di jendela kanan dan pilih "Baru" -> "Nilai DWORD (32-bit)" untuk membuat nilai baru dengan nama "NoAutoUpdate." Klik dua kali pada nilai baru tersebut dan atur nilainya menjadi 1.

Simpan perubahan dan restart komputer Anda untuk menerapkan perubahan.
<hr>

### Menonaktifkan pembaruan Windows 11 menggunakan Group Policy Editor.

    1. Untuk membuka Group Policy Editor, tekan tombol Windows + R, ketik "gpedit.msc," dan tekan Enter.
    2. Navigasikan ke lokasi berikut: Kebijakan Komputer Lokal > Konfigurasi Komputer > Template Administratif > Komponen Windows > Pembaruan Windows > Kelola pengalaman pengguna akhir.
    3. Klik dua kali pada opsi "Konfigurasikan Pembaruan Otomatis" di jendela sebelah kanan dan pilih opsi "Dinonaktifkan" untuk menonaktifkan pembaruan Windows 11.
  <hr>

  ### Menghentikan pembaruan Windows 11 dengan mengatur Koneksi Terukur (Metered Connection).

    1. Klik tombol Mulai -> Pengaturan untuk membuka Pengaturan Windows 11.
    2. Klik "Jaringan & Internet" di panel sebelah kiri.
    3. Klik "Properties" di jendela sebelah kanan.
    4. Aktifkan sakelar opsi "Koneksi Terukur."
    5. Meskipun begitu, klik "Pembaruan Windows" di panel sebelah kiri dan klik "Opsi lanjutan" di jendela sebelah kanan. Matikan juga opsi "Unduh pembaruan melalui meteran."
