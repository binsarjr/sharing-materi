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