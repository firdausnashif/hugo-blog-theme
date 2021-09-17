---
title: Cara Setting Hotspot Mikrotik
subtitle: Cara mudah setting hotspot dengan mudah
date: 2020-12-13T00:00:00.000Z
summary: ""
draft: false
featured: false
authors:
  - admin
  - 吳恩達
lastmod: 2020-12-13T00:00:00.000Z
tags:
  - Academic
  - 开源
categories:
  - Demo
  - 教程
projects: []
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)"
  focal_point: ""
  placement: 2
  preview_only: false
  filename: featured.jpg
---
## Langkah

1. Setting pengaturan ip mikrotik dan buat lokal bisa internetan biasa
2. Pilih menu **IP**, lanjutkan dengan **Hotspot**, dan **Hotspot Setup**.
3. Tentukan *Hotspot Interface* yang akan digunakan (pilih yang akan dihubungkan dengan Access Point), biasanya digunakan **ether2**, lalu klik **Next**.
4. Tentukan *IP address gateway* untuk *hotspot*, proses ini biasanya akan terisi secara otomatis dan mengarah pada **IP address ether2**.
5. Selanjutnya tentukan *pool dhcp server* atau *range ip address* yang akan diberikan pada *user*, klik **Next**.
6. Pada tahapan penentuan **SSL**, kamu tidak perlu mengisinya dan cukup pilih **None**, klik **Next**.
7. Selanjutnya pengisian smtp server untuk *hotspot*, jika kamu tidak memilikinya, isi saja dengan 0.0.0.0 lalu tekan **Next**.
8. Input *DNS server* yang akan digunakan di dalam jaringan *hotspot*, misalnya kamu bisa memasukkan *IP DNS* *provider* internet atau milik server seperti Google.
9. Isikan nama domain DNS Lokal yang akan mengarahkan ke halaman *login.* Halaman ini harus diberi nama domain lokal, kemudian klik Next.
10. Buat *username* dan *password* untuk pengguna, untuk percobaan isikan saja *test* di kedua kolom tersebut.
11. Setelah selesai, akan muncul *textbox* yang memberikan informasi penyetelan selesai dilakukan. Coba sambungkan dengan perangkat, maka kamu akan mendapati halaman *login* yang tadi sudah dibuat.
12. Proses penyetelan selesai, kamu tinggal menambahkan *user* yang bisa terkoneksi pada jaringan yang sudah kamu buat. Penambahan *user* ini sekaligus bisa memberikan batasan kecepatan, durasi penggunaan, serta batas total *user* yang bisa tersambung. Akan sangat efektif diterapkan di tempat usaha milik kamu.

<!--EndFragment-->