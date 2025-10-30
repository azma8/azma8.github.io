---
layout: post
title: CasaOS bukan OS yang pada umumnya, tapi ini tool
---

**CasaOS** adalah platform open-source yang memudahkan dalam mengelola container dan aplikasi self-hosted via web ui. CasaOS secara otomatis menginstal dan bisa mengelola Docker.

## Kenapa CasaOS

Bagi yang ingin menjalankan aplikasi/service pribadi di server lab pribadi, mini PC, atau Raspberry Pi, CasaOS memudahan penggunaan dan fleksibilitas Docker.  
fitur CasaOS:

- **UI keren dan simple** — Semua container bisa dimonitor dan dikontrol langsung dari browser tanpa perintah terminal.

![_config.yml]({{ site.baseurl }}/images/casaos/casaos-ui.png)

- **App Store bawaan** — Menyediakan banyak aplikasi populer dan umum digunakan yang bisa diinstal dengan mudah.  

![_config.yml]({{ site.baseurl }}/images/casaos/casaos-app-store.png)

- **Manage File dan Sharing File** — CasaOS punya file manager untuk mengelola file di host tempat CasaOS terpasang, dan file tersebut bisa dibagikan dengan mudah karena CasaOS sudah pakai Samba untuk file sharing.

![_config.yml]({{ site.baseurl }}/images/casaos/casaos-file.png)

- **Berbasis Docker** — Kompatibel dengan seluruh image di Docker Hub.  
- **Open-source dan ringan** — Dapat berjalan di semua perangkat berbasis linux.  

Dengan CasaOS, kita bisa memiliki lingkungan self-hosting yang mudah kelola.

## Instalasi CasaOS

CasaOS bisa diinstal langsung pada os linux dan hampir semua linux bisa diinstall CasaO.  
Proses instalasinya simple, cukup jalankan perintah:

```
curl -fsSL https://get.casaos.io | sudo bash
```

dengan user root atau command `sudo`

source: https://casaos.zimaspace.com/