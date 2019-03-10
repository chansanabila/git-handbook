<div align="justify">

# Git Handbook DOT Indonesia
Standar dan panduan bagi engineer DOT Indonesia atau vendor untuk workflow development menggunakan git.

Kunjungi [Development Stack & Tools](https://github.com/pt-dot/development-stack-tools) untuk melihat daftar aplikasi dan perangkat development yang dibutuhkan

---
# Table of Contents
1. [Perintah Dasar dalam Git](#perintah-dasar-dalam-git)
2. Main Branches
3. Supporting Branches
---

## Perintah Dasar dalam Git
Untuk menggunakan Git, developer menggunakan perintah khusus untuk menyalin, membuat dan menggabungkan kode dalam suatu project. Berikut perintah dasar yang sering digunakan oleh para developer:

- **`git init`**
    <br/>Perintah ini digunakan untuk menginisialisasi _repositori_ Git baru.

- **`git clone`**
    <br/>Perintah ini digunakan untuk menyalin suatu project ke komputer atau _local repository_ developer. Salinan tersebut berupa keseluruhan file, history dan branch.

- **`git add`**
    <br/>Git akan secara otomatis melacak perubahan file, akan tetapi perlu dilakukan perintah ini sebelum perubahan tersebut dapat dicommit dan dipush. Perintah ini akan menambahkan semua perubahan kode yang kita lakukan menjadi `staged files`.

- **`git commit`**
    <br/>Perintah ini dilakukan untuk menyimpan snapshot ke history project, developer dapat menambahkan pesan perubahan apa saja yang telah dilakukan. Perubahan apapun yang dimasukkan ke `staged files` melalui perintah `git add` akan menjadi bagian dari snapshot dengan `git commit`.

- **`git status`**
    <br/>Perintah ini dilakukan untuk mengetahui perubahan yang belum terlacak, termodifikasi maupun yang sudah berubah menjadi `staged files`. Selain itu developer dapat mengetahui posisi branch yang sedang aktif.

- **`git branch`**
    <br/>Perintah ini dilakukan untuk mengetahui posisi branch yang sedang aktif.

- **`git pull`**
    <br/>Perintah ini dilakukan ketika developer ingin melakukan pembaruan dari _remote repository_. Biasanya dilakukan ketika developer lain melakukan perubahan pada branch lain dan kita ingin mendapatkan perubahan tersebut pada branch lokal kita, atau melakukan sinkronisasi perubahan antar branch.

- **`git push`**
    <br/>Memperbarui _remote repository_ dengan perubahan yang dilakukan di _local repository_.

</div>