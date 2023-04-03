Berikut adalah beberapa contoh wildcard pada terminal:

1.  `*` : Mengembalikan semua file atau direktori di dalam direktori saat ini.
2.  `?` : Mengembalikan file atau direktori yang memiliki nama tepat satu karakter.
5.  `{ }` : Mengembalikan file atau direktori yang memiliki nama sesuai dengan salah satu pola yang diberikan. Misalnya, `{*.txt,*.pdf}` mengembalikan file yang memiliki ekstensi `.txt` atau `.pdf`.

Contoh penggunaan wildcard pada terminal:

1.  `ls *.txt` : Menampilkan semua file yang berakhiran dengan `.txt` di dalam direktori saat ini.
2.  `ls d?r` : Menampilkan semua direktori yang memiliki nama 3 karakter, diawali dengan `d` dan diakhiri dengan `r`.
	1.  `ls *.{txt,pdf}` : Menampilkan semua file yang memiliki ekstensi `.txt` atau `.pdf` di dalam direktori saat ini.