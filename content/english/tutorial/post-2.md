---
title: "Memperbaiki taskbar tidak berfungsi windows"
meta_title: ""
description: "Taskbar Dan File Explorer"
date: 2022-04-04T05:00:00Z
image: "/images/Windows_11_HDR.jpg"
categories: ["Tutorial"]
author: "Sam Wilson"
tags: ["Windows", "Tutorial"]
draft: false
---

Taskbar pada Windows 11 terkadang tidak berfungsi atau tidak merespon. Melalui postingan ini, kami akan memberikan solusinya.

Microsoft mengenalkan desain baru untuk taskbar di Windows 11 dengan ikon terpusat di tengah. Dengan desain baru, tidak lantas taskbar ini bebas dari permasalahan. Masalah taskbar tidak berfungsi yang sebelumnya terjadi di Windows 10, kini diterjadi juga di Windows 11.

## Restart Windows Explorer

1. Buka Task Manager dengan menekan tombol <a><b> Ctrl+Shift+Esc </b></a>.

2. Setelah Task Manager terbuka, pastikan tab Processes terpilih.

3. Pada bagian kolom Name, cari Windows Explorer. Kemudian klik kanan Restart.

{{< image src="images/windows-explorer-restart-768x372.webp" caption="" alt="alter-text" height="" width="" position="center" command="fill" option="q100" class="img-fluid" title="image title"  webp="true" zoomable="true" >}}

4. Tunggu beberapa detik, taskbar mungkin akan sementara menghilang selama proses restart. Setelah taskbar kembali muncul, anda bisa memeriksa kembali apakah taskbar sudah normal.

## Restart PC

Jika restart Windows Explorer tidak berdampak apa-apa, coba restart PC atau laptop anda. Karena anda sudah terbiasa mematikan atau me-restart melalui menu Start Windows, mungkin anda akan kebingungan bagaimana cara me-restart-nya. Ada banyak alternatif mematikan atau merestart Windows, diantaranya melalui tombol <a><b>ALT+F4</a></b> dan cara lainnya melalui tombol <a><b>CTRL+ALT+DEL.</a></b>

Memperbaik File Sistem

Metode berikutnya, anda bisa mencoba mengatasi masalah taskbar Windows 11 yang tidak berfungsi dengan memperbaiki file sistem. Cara ini seharusnya tidak berisiko namun segala kemungkinan bisa terjadi.

## Berikut adalah cara memperbaiki file sistem di Windows.

1. Tekan tombol Windows + R untuk membuka Run. Ketik cmd untuk Command Prompt dan tekan <a><b>ENTER.</a></b>

{{< notice "tip" >}}
- Dism /Online /Cleanup-Image /ScanHealth
- Dism /Online /Cleanup-Image /RestoreHealth
- sfc /scannow
{{< /notice >}}

2. Setelah jendela Command Prompt terbuka, masukkan perintah berikut secara berurutan.

3. Setelah menjalankan perintah di atas, tutup jendela Command Prompt, kemudian restart PC Anda.

## Restart System Services

Metode lain untuk memperbaiki masalah taskbar Windows 11 yang tidak berfungsi adalah memulai ulang beberapa system service melalui Task Manager. Mari kita lihat secara rinci.

1. Tekan tombol <a><b>Ctrl+Shift+Esc</a></b> pada keyboard untuk membuka task manager.

2. Arahkan dan klik tab Details.

3. Sekarang, tutup service berikut, caranya klik kanan pada nama service, pilih End task.

{{< notice "tip" >}}

- ShellExperienceHost.exe
- SearchIndexer.exe
- SearchHost.exe
- RuntimeBroker.exe

{{< /notice >}}

4. Setelah selesai, Reboot PC, dan taskbar akan mulai berfungsi.

## Semoga Tips Ini bisa membantu 🙏.