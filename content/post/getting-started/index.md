---
title: Cara Setting Hotspot Mikrotik
subtitle: Cara mudah setting hotspot dengan mudah
date: 2020-12-13T00:00:00.000Z
summary: Welcome 👋 We know that first impressions are important, so we've
  populated your new site with some initial content to help you get familiar
  with everything in no time.
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
  filename: download.jfif
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

## Get Started

* 👉 **[Create a new site](https://wowchemy.com/templates/)**
* 📚 **[Personalize your site](https://wowchemy.com/docs/)**
* 💬 [Chat with the **Wowchemy community**](https://discord.gg/z8wNYzb) or **[Hugo community](https://discourse.gohugo.io)**
* 🐦 Twitter: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [\#MadeWithWowchemy](https://twitter.com/search?q=(%23MadeWithWowchemy%20OR%20%23MadeWithAcademic)&src=typed_query)
* 💡 [Request a **feature** or report a **bug** for *Wowchemy*](https://github.com/wowchemy/wowchemy-hugo-modules/issues)
* ⬆️ **Updating Wowchemy?** View the [Update Guide](https://wowchemy.com/docs/guide/update/) and [Release Notes](https://wowchemy.com/updates/)

## Crowd-funded open-source software

To help us develop this template and software sustainably under the MIT license, we ask all individuals and businesses that use it to help support its ongoing maintenance and development via sponsorship.

### [❤️ Click here to become a sponsor and help support Wowchemy's future ❤️](https://wowchemy.com/plans/)

As a token of appreciation for sponsoring, you can **unlock [these](https://wowchemy.com/plans/) awesome rewards and extra features 🦄✨**

## Ecosystem

* **[Hugo Academic CLI](https://github.com/wowchemy/hugo-academic-cli):** Automatically import publications from BibTeX

## Inspiration

[Check out the latest **demo**](https://academic-demo.netlify.com/) of what you'll get in less than 10 minutes, or [view the **showcase**](https://wowchemy.com/user-stories/) of personal, project, and business sites.

## Features

* **Page builder** - Create *anything* with **[widgets](https://wowchemy.com/docs/page-builder/)** and **[elements](https://wowchemy.com/docs/writing-markdown-latex/)**
* **Edit any type of content** - Blog posts, publications, talks, slides, projects, and more!
* **Create content** in **[Markdown](https://wowchemy.com/docs/writing-markdown-latex/)**, **[Jupyter](https://wowchemy.com/docs/import/jupyter/)**, or **[RStudio](https://wowchemy.com/docs/install-locally/)**
* **Plugin System** - Fully customizable [**color** and **font themes**](https://wowchemy.com/docs/customization/)
* **Display Code and Math** - Code highlighting and [LaTeX math](https://en.wikibooks.org/wiki/LaTeX/Mathematics) supported
* **Integrations** - [Google Analytics](https://analytics.google.com), [Disqus commenting](https://disqus.com), Maps, Contact Forms, and more!
* **Beautiful Site** - Simple and refreshing one page design
* **Industry-Leading SEO** - Help get your website found on search engines and social media
* **Media Galleries** - Display your images and videos with captions in a customizable gallery
* **Mobile Friendly** - Look amazing on every screen with a mobile friendly version of your site
* **Multi-language** - 34+ language packs including English, 中文, and Português
* **Multi-user** - Each author gets their own profile page
* **Privacy Pack** - Assists with GDPR
* **Stand Out** - Bring your site to life with animation, parallax backgrounds, and scroll effects
* **One-Click Deployment** - No servers. No databases. Only files.

## Themes

Wowchemy and its templates come with **automatic day (light) and night (dark) mode** built-in. Alternatively, visitors can choose their preferred mode - click the moon icon in the top right of the [Demo](https://academic-demo.netlify.com/) to see it in action! Day/night mode can also be disabled by the site admin in `params.toml`.

[Choose a stunning **theme** and **font**](https://wowchemy.com/docs/customization) for your site. Themes are fully customizable.

## License

Copyright 2016-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/wowchemy/wowchemy-hugo-modules/blob/master/LICENSE.md) license.