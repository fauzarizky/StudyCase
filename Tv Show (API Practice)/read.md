Ini adalah program untuk menampilakan daftar acara TV dengan AXIOS

Keterangan

*e.preventDefault();
supaya saat di click submit tidak akan refresh/pergi kehalaman lain

*document.querySelectorAll('img').forEach((img) => img.remove());
semua tag images yg ada di dalam body masing2nya akan dihapus 
menggunakan metode forEach dengan parameter img sebagai object masing2 element
dan masing2 element akan diremove,jadi pada saat melakukan submit pastikan dihapus terlebih dahulu,
baru generate tag img baru.

*Const Config
digunakan untuk melakukan query string
Q: kenapa dipisahkan didalam config?
A: karena bisa saja memerlukan beberapa query string atau key&valuenya
   jdi tidak hanya keywordnya saja/ q nya saja tpi bisa tambahkan embed/tvdb/imdb dll
   kita bisa tambahkan di dalam config

*Const res
untuk mendapatkan acara tv dari API tvmaze

*Const getImages 
untuk menampilkan gambar sesuai keyword yang diketikan
