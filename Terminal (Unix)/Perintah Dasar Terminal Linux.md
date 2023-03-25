Beberapa Perintah yang akan kita pelajari di modul ini:
- cd (change directory)
- ls (list)
- mkdir (make directory)
- touch (membuat file kosong)
- cat (melihat isi file)
- mv (memindahkan file atau direktori)
- cp (mengcopy file atau direktori)
- rm (menghapus file atau direktori)
- chmod (mengubah hak akses file)


### cd (change directory)
Change Directory (cd)

Perintah cd digunakan untuk berpindah antar direktori pada sistem operasi Linux. Berikut ini adalah sintaks perintah cd:

```bash
cd [nama_direktori]
```

Untuk berpindah ke direktori yang berada di dalam direktori saat ini, pengguna dapat menggunakan tanda slash (/) diikuti dengan nama direktori. Berikut ini adalah contoh perintah cd untuk berpindah ke direktori yang berada di dalam direktori saat ini:

```bash
cd /nama_direktori
```

Berikut ini beberapa variasi penggunaan perintah cd di terminal beserta penjelasannya:

1.  cd: Perintah cd tanpa argumen akan membawa pengguna ke direktori home mereka. Jadi, ketika perintah cd dieksekusi tanpa argumen, maka terminal akan membuka direktori home user tersebut.
    
2.  cd ~ : Tanda tilde (~) pada terminal Linux mengacu pada direktori home pengguna. Dengan menjalankan perintah "cd ~", pengguna dapat dengan mudah kembali ke direktori home mereka.
    
3.  cd .. : Perintah "cd .." akan membawa pengguna ke direktori induk dari direktori saat ini. Jadi, jika kita berada di dalam direktori "/home/user/Documents" dan menjalankan perintah "cd ..", maka kita akan berada di direktori "/home/user".
    
4.  cd - : Perintah "cd -" akan membawa pengguna kembali ke direktori sebelumnya yang mereka kunjungi. Misalnya, jika pengguna berada di direktori "/home/user/Documents" dan kemudian pindah ke direktori "/home/user/Pictures" dengan menjalankan "cd /home/user/Pictures", maka perintah "cd -" akan membawa mereka kembali ke direktori "/home/user/Documents".
    
5.  cd /path/to/directory : Perintah "cd /path/to/directory" akan membawa pengguna ke direktori yang ditentukan oleh path (path adalah jalur yang digunakan untuk menunjukkan lokasi direktori atau file). Path dapat dimulai dari direktori root ( / ) atau dari direktori saat ini.
   
6. cd / : Perintah "cd /" akan membawa pengguna langsung ke direktori root dari sistem file Linux. Ini berguna jika pengguna ingin menjelajahi seluruh struktur direktori dari sistem file Linux.
   
7. cd ~/Desktop : Perintah "cd ~/Desktop" akan membawa pengguna langsung ke direktori Desktop dari direktori home mereka. Ini berguna jika pengguna ingin dengan cepat mengakses file yang berada di Desktop.

[![asciicast](https://asciinema.org/a/569899.svg)](https://asciinema.org/a/569899)

### ls (list)
Perintah ls adalah salah satu perintah dasar di terminal Linux yang sering digunakan untuk melihat isi dari sebuah direktori.

Perintah ls adalah salah satu perintah dasar yang sangat berguna untuk menavigasi di dalam direktori pada sistem operasi Linux. Pengguna Linux dapat menggunakan perintah ini untuk melihat dan mengelola file dan direktori dengan mudah dan efisien.

Berikut adalah beberapa penjelasan mengenai perintah ls di terminal Linux:

1.  Menampilkan Isi Direktori Perintah ls digunakan untuk menampilkan isi dari sebuah direktori. Secara default, perintah ini akan menampilkan semua file dan direktori pada direktori aktif.
    
2.  Menggunakan Opsi Perintah ls memiliki banyak opsi yang dapat digunakan untuk menampilkan informasi lebih detail mengenai isi dari sebuah direktori. Beberapa opsi yang sering digunakan adalah:
    

-   -l : Menampilkan informasi secara rinci mengenai setiap file dan direktori seperti pemilik, grup, hak akses, ukuran, dan tanggal modifikasi.
-   -a : Menampilkan semua file, termasuk file yang dianggap tersembunyi. File yang dianggap tersembunyi diawali dengan titik (.) pada namanya.
-   -h : Menampilkan ukuran file dalam format yang mudah dibaca manusia.

3.  Menggabungkan Opsi Opsi pada perintah ls dapat digabungkan untuk menampilkan informasi yang lebih spesifik. Sebagai contoh, perintah "ls -alh" akan menampilkan semua file dan direktori, termasuk yang tersembunyi, dengan informasi rinci yang ditampilkan dalam format ukuran yang mudah dibaca manusia.
    
4.  Menggunakan Argumen Perintah ls dapat digunakan dengan argumen untuk menampilkan isi dari direktori tertentu. Sebagai contoh, perintah "ls /var/log" akan menampilkan semua file dan direktori pada direktori log.
    
5.  Menggunakan Argumen dan Opsi pada Perintah ls dapat digabungkan. Sebagai contoh, perintah "ls -a /var/log" akan menampilkan semua file dan direktori pada direktori log beserta file tersembunyinya.
    


Berikut adalah tutorial pembelajaran mengenai perintah ls di terminal Linux:

1. Menampilkan Isi Direktori Untuk menampilkan isi dari direktori aktif, cukup ketikkan perintah berikut di terminal:
```bash
ls
```
Perintah ini akan menampilkan semua file dan direktori yang ada pada direktori aktif.

2. Menggunakan Opsi Untuk menggunakan opsi pada perintah ls, cukup tambahkan opsi yang diinginkan setelah perintah ls. Sebagai contoh, untuk menampilkan informasi rinci mengenai setiap file dan direktori pada direktori aktif, ketikkan perintah berikut di terminal:
```bash
ls -l
```
Perintah ini akan menampilkan informasi secara rinci mengenai setiap file dan direktori pada direktori aktif.

Untuk menampilkan semua file, termasuk file yang dianggap tersembunyi, gunakan opsi -a. Sebagai contoh, untuk menampilkan semua file dan direktori pada direktori aktif, termasuk yang tersembunyi, ketikkan perintah berikut di terminal:
```bash
ls -a
```
Perintah ini akan menampilkan semua file dan direktori pada direktori aktif, termasuk yang tersembunyi.

Untuk menampilkan ukuran file dalam format yang mudah dibaca manusia, gunakan opsi -h. Sebagai contoh, untuk menampilkan ukuran file dan direktori pada direktori aktif dalam format yang mudah dibaca manusia, ketikkan perintah berikut di terminal:
```bash
ls -h
```

Perintah ini akan menampilkan ukuran file dan direktori pada direktori aktif dalam format yang mudah dibaca manusia.

3. Menggabungkan Opsi Opsi pada perintah ls dapat digabungkan untuk menampilkan informasi yang lebih spesifik. Sebagai contoh, untuk menampilkan semua file dan direktori, termasuk yang tersembunyi, dengan informasi rinci yang ditampilkan dalam format ukuran yang mudah dibaca manusia, ketikkan perintah berikut di terminal:
```bash
ls -lah
```

4. Menggunakan Argumen
   Untuk menampilkan isi dari direktori tertentu, tambahkan argumen direktori setelah perintah ls. Sebagai contoh, untuk menampilkan semua file dan direktori pada direktori /var/log, ketikkan perintah berikut di terminal:
```bash
ls /var/log
```
5. Menggunakan Argumen dan Opsi
   Untuk menampilkan isi dari direktori, tambahkan opsi setelah perintah ls, tambahkan argumen direktori setelah opsi. Sebagai contoh, untuk menampilkan semua file dan direktori pada direktori /var/log dan tampilkan juga file tersembunyi, ketikkan perintah berikut di terminal:
```bash
ls -a /var/log
```

[![asciicast](https://asciinema.org/a/569910.svg)](https://asciinema.org/a/569910)

### mkdir (make directory)