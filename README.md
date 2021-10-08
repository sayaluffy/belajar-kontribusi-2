[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

# Belajar Kontribusi
Repositori untuk belajar kontribusi open source project.

## Fork Repositori
Fork repositori ini dengan cara menekan tombol fork di sebelah kan atas. 

![fork repositori](screenshot/image-1.png)

## Clone repositori hasil fork
Selanjutnya, clone repo hasil fork yang ada di akun kamu ke komputer local. Tekan tombol Code, lalu tekan icon *copy to clipboard* .
![fork](screenshot/image-2.png)

![fork](screenshot/image-3.png)


Buka terminal lalu run git command di bawah ini:
```
git clone "url yang udah dicopy"
```



Misalnya:
```
git clone https://github.com/username-kamu/belajar-kontribusi.git
```
di mana `username-kamu` diisi sama username akun GitHub kamu.

## Buat branch baru
Setelah repositori di-clone, buka folder repositori:

```
cd belajar-kontribusi
```
Lalu buat branch baru menggunakan command `git checkout`:
```
git checkout -b <add-nama-kamu>
```

Contohnya:
```
git checkout -b add-gun-gun
```
(Nama branch-nya bebas. Cuma mesti disesuaikan sama tujuan branch dibuat ya.)

## Modifikasi dan Commit
Buat file baru di dalam folder `Contributors` dengan format `nama-kamu.md` contohnya (`gun-gun-priatna.md`). Tentang markdown bisa kamu baca-baca cheatsheet-nya [di sini yaa.](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Buka file `nama-kamu.md`, tuliskan nama dan deskripsi.

```
Name: [nama-kamu](url-akun-github) 
About: [Deskripsi tentang kamu]
```

Contoh:
```
Name: [Gun Gun Priatna](https://github.com/gungunpriatna) 
About: Saya seorang web developer
```

**Note:** Kamu boleh menuliskan asal untuk nama dan deskripsinya ya, karena ini tujuannya untuk belajar, bukan untuk mengumpulkan data.

Run command `git status` buat lihat modifikasi apa saja yang udah kamu lakukan. 

Selanjutnya tambahkan dengan menggunakan command `git add`:

```
git add Contributors/nama-kamu.md
```

Lalu commit:

```
git commit -m "Add <nama-kamu> ke daftar kontributor"
```

Ubah <nama-kamu> sama nama kamu ya.

## Push ke GitHub
Push dengan command `git push`:
```
git push origin <add-nama-kamu>
```
ubah `<add-nama-kamu>` dengan nama branch yang udah dibuat.

## Pull Request
Kalau kamu buka repositori kamu di GitHub, kamu bisa lihat tombol `Compare & pull request` button.  Tekan tombol tersebut.

![fork](screenshot/image-4.png)

Nah selanjutnya tekan tombol Create pull request.

![fork](screenshot/image-5.png)


