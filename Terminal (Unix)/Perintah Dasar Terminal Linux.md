Beberapa Perintah yang akan kita pelajari di modul ini:
- cd (change directory)
- ls (list)
- mkdir (make directory)
- touch (membuat file kosong)
- cat (melihat isi file)
- mv (memindahkan file atau direktori)
- cp (mengcopy file atau direktori)
- rm (menghapus file atau direktori)


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
Perintah `mkdir` digunakan untuk membuat direktori atau folder baru di Linux. Berikut adalah sintaks dasar dari perintah `mkdir`:
```bash
mkdir [opsi] nama_direktori
```

Berikut adalah beberapa opsi umum yang dapat digunakan dengan perintah `mkdir`:

-   `-p`: Membuat direktori induk jika belum ada. Misalnya, jika Anda ingin membuat direktori bernama `neuversity/terminal/dasar`, Anda dapat menggunakan perintah `mkdir -p neuversity/terminal/dasar`.

Contoh penggunaan: Jika Anda ingin membuat direktori baru bernama "belajar_linux", Anda dapat mengetikkan perintah berikut di terminal:
```bash
mkdir belajar_linux
```

Jika Anda ingin membuat direktori "belajar_linux" beserta dengan direktori induknya, misalnya direktori "pemula", Anda dapat menggunakan opsi `-p` seperti ini:
```bash
mkdir -p pemula/belajar_linux
```


Dengan menggunakan opsi `-p`, direktori "pemula" akan dibuat terlebih dahulu jika belum ada, kemudian direktori "belajar_linux" akan dibuat di dalamnya.


### Touch  (membuat file kosong)
Perintah `touch` digunakan untuk membuat file kosong atau mengubah waktu modifikasi dari file yang sudah ada di Linux.

Berikut adalah sintaks dasar dari perintah `touch`:


```bash
touch [opsi] nama_file
```


Berikut adalah beberapa opsi umum yang dapat digunakan dengan perintah `touch`:

-   `-a`: Mengubah hanya waktu akses file.
-   `-m`: Mengubah hanya waktu modifikasi/edit file.
-   `-c`: Hanya membuat file jika file tersebut belum ada.

Contoh Penggunaan

Jika Anda ingin membuat file kosong baru bernama "catatan.txt", Anda dapat mengetikkan perintah berikut di terminal:


```bash
touch catatan.txt
```

Jika file "catatan.txt" sudah ada dan Anda ingin mengubah waktu modifikasi file tersebut menjadi waktu saat ini, Anda dapat menggunakan opsi `-m` seperti ini:


```bash
touch -m catatan.txt
```

Jika Anda ingin membuat file "catatan.txt" hanya jika file tersebut belum ada, Anda dapat menggunakan opsi `-c` seperti ini:


```bash
touch -c catatan.txt
```

Dengan menggunakan opsi `-c`, file "catatan.txt" hanya akan dibuat jika file tersebut belum ada. Jika file sudah ada, perintah `touch` tidak akan melakukan apa-apa.


### cat (melihat isi file)
Perintah `cat` adalah singkatan dari "concatenate", yang berarti menggabungkan atau menggabungkan file. Namun, perintah `cat` juga digunakan untuk membaca, membuat, dan mengedit file di Linux.

Berikut adalah sintaks dasar dari perintah `cat`:


```bash
cat [opsi] [nama_file]
```

Berikut adalah beberapa opsi umum yang dapat digunakan dengan perintah `cat`:

-   `-n`: Menampilkan nomor baris pada setiap baris file.
-   `-b`: Menampilkan nomor baris pada setiap baris file, tetapi hanya pada baris yang tidak kosong.
-   `-s`: Menggabungkan beberapa baris kosong menjadi satu baris kosong.

**Membaca Isi File**



Untuk membaca isi file di terminal, cukup ketikkan perintah `cat` diikuti dengan nama file yang ingin dibaca. Misalnya, jika Anda ingin membaca isi file "catatan.txt", ketikkan perintah berikut:

```bash
cat catatan.txt
```

**Membuat File**

Untuk membuat file baru, Anda dapat menggunakan perintah `cat` bersama dengan operator redirect `>` untuk mengalirkan output dari perintah `cat` ke file yang baru. Misalnya, jika Anda ingin membuat file baru bernama "pesan.txt", Anda dapat mengetikkan perintah berikut:

```
cat > pesan.txt
```

Setelah Anda mengetikkan perintah ini, terminal akan menunggu input Anda. Ketikkan teks yang ingin Anda masukkan ke file, kemudian tekan tombol `CTRL + D` untuk menyimpan file dan keluar dari mode input.

**Menggabungkan File**

Anda juga dapat menggunakan perintah `cat` untuk menggabungkan dua atau lebih file. Misalnya, jika Anda memiliki file "file1.txt" dan "file2.txt", dan ingin menggabungkan kedua file tersebut menjadi satu file baru bernama "gabungan.txt", ketikkan perintah berikut:


```bash
cat file1.txt file2.txt > gabungan.txt
```

**Menampilkan Nomor Baris**

Anda dapat menggunakan opsi `-n` atau `-b` untuk menampilkan nomor baris pada setiap baris file. Misalnya, jika Anda ingin menampilkan isi file "catatan.txt" beserta nomor baris pada setiap baris, ketikkan perintah berikut:

```bash
cat -n catatan.txt
```

**Menggabungkan Baris Kosong**

Anda dapat menggunakan opsi `-s` untuk menggabungkan beberapa baris kosong menjadi satu baris kosong. Misalnya, jika Anda memiliki file "catatan.txt" yang berisi beberapa baris kosong berturut-turut, dan ingin menggabungkan baris kosong tersebut menjadi satu baris kosong, ketikkan perintah berikut:


```bash
cat -s catatan.txt
```

### mv (memindahkan file atau direktori)
Perintah `mv` di Linux digunakan untuk memindahkan atau mengubah nama file atau direktori. Berikut adalah sintaks dasar dari perintah `mv`:


```bash
mv [opsi] sumber tujuan
```

Di mana `sumber` adalah nama file atau direktori yang akan dipindahkan atau diubah namanya, dan `tujuan` adalah lokasi baru atau nama baru untuk file atau direktori tersebut.

Berikut adalah beberapa opsi umum yang dapat digunakan dengan perintah `mv`:

-   `-i`: Meminta konfirmasi sebelum menimpa file atau direktori yang sudah ada di lokasi tujuan.
-   `-n`: Tidak menimpa file atau direktori yang sudah ada di lokasi tujuan.
-   `-v`: Menampilkan output verbos saat menjalankan perintah `mv`.

**Contoh Penggunaan**

**Memindahkan File**

Jika Anda ingin memindahkan file "file1.txt" dari direktori "dir1" ke direktori "dir2", Anda dapat menggunakan perintah berikut:


```bash
mv dir1/file1.txt dir2/
```

Di mana `/` pada akhir direktori "dir2" menunjukkan bahwa "file1.txt" akan dipindahkan ke direktori "dir2".

Jika Anda ingin mengubah nama file "file1.txt" menjadi "file2.txt", Anda dapat menggunakan perintah berikut:

```bash
mv file1.txt file2.txt
```

**Memindahkan dan Mengubah Nama Direktori**

Jika Anda ingin memindahkan dan mengubah nama direktori "dir1" menjadi "dir2", Anda dapat menggunakan perintah berikut:


```bash
mv dir1/ dir2/
```

**Meminta Konfirmasi Sebelum Menimpa File atau Direktori**

Jika Anda ingin memindahkan file "file1.txt" dari direktori "dir1" ke direktori "dir2", tetapi ingin meminta konfirmasi sebelum menimpa file dengan nama yang sama di direktori "dir2", Anda dapat menggunakan opsi `-i` seperti ini:


```bash
mv -i dir1/file1.txt dir2/
```

**Tidak Menimpa File atau Direktori yang Sudah Ada**

Jika Anda ingin memindahkan file "file1.txt" dari direktori "dir1" ke direktori "dir2", tetapi tidak ingin menimpa file dengan nama yang sama di direktori "dir2", Anda dapat menggunakan opsi `-n` seperti ini:


```bash
mv -n dir1/file1.txt dir2/
```

**Menampilkan Output Verbose**

Jika Anda ingin menampilkan output verbos saat menjalankan perintah `mv`, Anda dapat menggunakan opsi `-v` seperti ini:


```bash
mv -v file1.txt file2.txt
```

Dengan menggunakan opsi `-v`, perintah `mv` akan menampilkan output yang lebih detail saat menjalankan perintah.


### cp (mengcopy file atau direktori)
Perintah `cp` digunakan untuk menyalin file atau direktori di Linux. Berikut adalah sintaks dasar dari perintah `cp`:


```bash
cp [opsi] sumber tujuan
```

-   `sumber`: merupakan path file atau direktori yang akan disalin.
-   `tujuan`: merupakan path lokasi tempat file atau direktori akan disimpan.

Berikut adalah beberapa opsi umum yang dapat digunakan dengan perintah `cp`:

-   `-r`: Meng-copy direktori secara rekursif (termasuk semua sub-direktori dan file di dalamnya).
-   `-i`: Meminta konfirmasi sebelum menimpa file tujuan yang sudah ada.

**Contoh penggunaan**

1.  Menyalin file
    Jika Anda ingin menyalin file bernama `file1.txt` dari direktori `/home/user1` ke direktori `/home/user2`, Anda dapat menggunakan perintah berikut:
    
    
    ```bash
cp /home/user1/file1.txt /home/user2/
```
    
    Jika file `file1.txt` sudah ada di direktori `/home/user2`, perintah ini akan menimpanya tanpa memberikan peringatan.
    
    Jika Anda ingin meminta konfirmasi sebelum menimpa file tujuan yang sudah ada, Anda dapat menggunakan opsi `-i` seperti ini:

    
    ```bash
cp -i /home/user1/file1.txt /home/user2/
```
    
    Dengan menggunakan opsi `-i`, perintah `cp` akan meminta konfirmasi sebelum menimpa file tujuan yang sudah ada.
    
2.  Menyalin direktori
    
    Jika Anda ingin menyalin direktori `dir1` beserta semua sub-direktori dan file di dalamnya dari direktori `/home/user1` ke direktori `/home/user2`, Anda dapat menggunakan perintah berikut:
    
    
    ```bash
cp -r /home/user1/dir1 /home/user2/
```
    
    Dengan menggunakan opsi `-r`, perintah `cp` akan menyalin direktori `dir1` secara rekursif, termasuk semua sub-direktori dan file di dalamnya. 



### rm (menghapus file atau direktori)
Perintah `rm` digunakan untuk menghapus file atau direktori di Linux. Berikut adalah sintaks dasar dari perintah `rm`:


```bash
rm [opsi] nama_file
```

Berikut adalah beberapa opsi umum yang dapat digunakan dengan perintah `rm`:

-   `-r`: Menghapus direktori beserta seluruh isi di dalamnya secara rekursif.
-   `-f`: Menghapus file atau direktori tanpa meminta konfirmasi terlebih dahulu.

**Peringatan**: Perintah `rm` dapat menghapus file atau direktori secara permanen, sehingga pastikan Anda telah memilih file atau direktori yang ingin dihapus dengan benar sebelum mengeksekusi perintah ini.

**Contoh penggunaan**

1.  Menghapus file bernama `catatan.txt`:

    
    ```bash
rm catatan.txt
```
    
2.  Menghapus direktori `data` beserta seluruh isi di dalamnya:
    
    
    ```bash
rm -r data/
```
    
3.  Menghapus file atau direktori tanpa meminta konfirmasi terlebih dahulu:
    
    ```bash
rm -rf nama_file_atau_direktori/
```
    
    Perintah di atas akan menghapus `nama_file_atau_direktori` beserta seluruh isi di dalamnya tanpa meminta konfirmasi terlebih dahulu.
    

**Catatan**: Pastikan Anda telah memilih file atau direktori yang ingin dihapus dengan benar sebelum mengeksekusi perintah `rm`. Sekali dihapus, file atau direktori tersebut tidak dapat dikembalikan.