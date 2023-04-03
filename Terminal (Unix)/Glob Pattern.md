Berikut adalah beberapa contoh glob pattern:

1.  `*.txt` : Mengembalikan semua file yang berakhiran dengan `.txt`.
2.  `?abc.txt` : Mengembalikan semua file yang memiliki nama 4 karakter, diawali dengan satu karakter apa saja dan diakhiri dengan `abc.txt`.
3.  `dir/**/*.txt` : Mengembalikan semua file yang berakhiran dengan `.txt` dalam semua direktori yang ada dalam direktori `dir`.
4.  `file.[0-9]` : Mengembalikan semua file yang memiliki nama `file` diikuti dengan satu digit angka.
5.  `*[aeiou]` : Mengembalikan semua file yang memiliki nama yang diakhiri dengan salah satu huruf vokal.
6.  `dir/{file1,file2}.txt` : Mengembalikan semua file yang memiliki nama `file1.txt` atau `file2.txt` dalam direktori `dir`.
7.  `dir/**/[0-9]*.txt` : Mengembalikan semua file yang memiliki nama yang diawali dengan satu atau lebih digit angka dan diakhiri dengan `.txt` dalam semua direktori yang ada dalam direktori `dir`.