Tugas 1 Alpro II :
Melakukan Inisialisasi repository menggunakan git (CLI) dan buat clonenya di Github. Lalu, lakukan first commit berupa file README.md
Langkah - Langkah :
1. Download dan Install Git pada link website berikut : 
(https://git-scm.com/download/win)
2. Jalankan Git Bash
3. Lakukan Konfigurasi awal pada Git Bash
4. Daftar(apabila belum memiliki di akun Github) atau Login(Apabila suda memiliki akun di Github) akun di Github 
5. Membuat repository baru 
6. Membuat file dengan ekstensi markdown pada folder Tugas-1-Alpro-II di file direktori local (laptop). Setelah membuat file README.md di folder Tugas-1-Alpro-II, klik kanan pada folder tersebut kemudian klik git bash here
7. Melakukan push ke github yaitu git config (memasukkan konfigurasi ke dalam gitnya berupa username dan user email sesuai akun di github)
8. Membuat folder tugas-pertama di laptop menjadi repository git/melakukan inisialisasi repository dilaptop kita, dengan menggunakan git init. Istilahnya kita meminta git untuk mengawasi folder ini. Setelah menulis git init di git bash dan dienter, didalam folder tugas-pertama akan muncul folder .git (otomatis folder tugas-pertama akan menjadi repo git dengan branch master)
9. Menuliskan git status, nantinya git akan memberi tahu kita ada file apa yang baru, file apa yang berubah dan belum di commit dalam folder tugas-pertama ini. Setelah dienter, akan terdapat informasi On Branch Master (sekarang lagi berada di branch master), No Commit yet (belum melakukan commit), dan ada Untracked files bernama README.md (berwarna merah), agar bisa dicommit file README.md disimpan dulu dalam staging area
10. Menambahkan file README.md kedalam staging area agar bisa dicommit dengan git add . Setelah itu ketika kita tulis git status untuk memeriksa apakah file README.md sudah disimpan dalam staging area. (informasi dalam git status akan berubah, file README.md sudah berwarna hijau artinya file ini sudah disimpan dalam staging area dan siap untuk di commit).
11. Menuliskan git commit dengan parameter -m “mencoba untuk tugas pertama” (menambahkan message mencoba pesan pertama” disarankan disini menulis mesaage yang jelas) kemudian dienter akan muncul beberapa informasi, master (root-commit) artinya ada commit ke branch master dan ada hash (penanda berupa kode), ada 1 file yang berubah dan ada 5 baris dalam file tersebut.
12. Menuliskan git status kembali nantinya akan muncul informasi nothing to commit working tree clean artinya file sudah dicommit dari staging area dan tidak ada file di working tree.
13. Mengelola server pusat untuk hosting repository git saya dengan menggunakan git remote
14. Membuat remote baru yang disebut origin 
15. Melakukan push dengan git push parameternya -u origin master untuk memasukkan ke clone di github dari repository local(disini artinya lakukan push commit dari cabang lokal bernama master ke remote yang bernama origin)
16. Mengecek di repository github apakah project README.md sudah terupload di github atau belum.
17. Selesai

Operasi dan Fungsi Dasar Git :
1. Git config
Salah satu perintah git yang paling banyak digunakan adalah git config, yang bisa digunakan untuk mengatur konfigurasi tertentu sesuai keinginan pengguna, seperti email, algoritma untuk diff, username, format file, dll.
2. Git init
Perintah ini digunakan untuk membuat repositori baru
3. Git add
Perintah git add bisa digunakan untuk menambahkan file ke index
4. Git clone
Perintah git clone digunakan untuk checkout repositori. Jia repositori berada di remove server
5. Git commit
Perintah git commit digunakan untuk melakukan commit pada perubahan ke head. Ingat bahwa perubahan apapun yang di-commit tidak akan langsung ke remote repository
6. Git status
Perintah git status menampilkan daftar file yang berubah bersama dengan file yang ingin di tambahkan atau di-commit
7. Git push
Perintah git dasar lainnya. Push akan mengirimkan perubahan ke master branch dari remote repository yang berhubungan dengan direktori kerja Anda
8. Git checkout
Perintah git checkout bisa digunakan untuk membuat branch atau untuk berpindah diantaranya
9. Git remote
Perintah git remote akan membuat user terhubung ke remote repository
10. Git branch
Perintah git branch bisa digunakan untuk me-list, membuat atau menghapus branch
11. Git pull
Untuk menggabungkan semua perubahan yang ada di remote repository ke direktori lokal
12. Git merge
Perintah merge digunakan untuk menggabungkan sebuah branch ke branch aktif
13. Git diff
Perintah git diff digunakan untuk menampilkan conflicts. Untuk melihat conflicts dengan file dasar
14. Git tag
Tagging digunakan untuk menandai commits tertentu
15. Git log
Dengan menjalankan peritah ini akan menampilkan daftar commits yang ada di branch beserta detail-nya
16. Git reset
Untuk me-reset index dan bekerja dengan kondisi commit paling baru
17. Git rm
Gunakan perintah ini untuk menghapus file dari index dan direktori kerja
18. Git stash
Mungkin inilah salah satu perintah dasar git yang jarang digunakan orang, yang bisa membantu menyimpan perubahan yang tidak langsung di-commit, namun hanya sementara
19. Git show
Untuk menampilkan informasi tentang object pada git
20. Git fetch
Perintah ini digunakan untuk menampilkan semua object dari remote repository yang tidak berada di direktori kerja lokal
21. Git ls-tree
Untuk menampilkan susunan object berdasarkan nama dan mode setiap item, dan nilai blob SHA-1, gunakan perintah git ls-tree
22. Git cat-file
Menggunakan nilai SHA-1, menampilkan tipe object dengan menggunakan perintah git cat-file
23. Git prep
git prep mengizinkan pengguna mencari frase dan/atau kata yang berada di dalam direktori
24. Gitk
gitk adalah tampilan grafis dari repository lokal yang bisa dipanggil
25. Git instaweb
Dengan perintah git instaweb, web server bisa dijalan berdampingan dengan repository lokal. Nantinya web browser akan langsung diarahkan ke server tersebut
26. Git gc
Untuk mengoptimasi repository melalui garbage collection, yang akan membersihkan file yang tidak dibutuhkan dan mengoptimasinya
27. Git archive
Perintah git archive memungkinkan user membuat file zip atau tar yang mengandung susunan repository
28. Git prune
Melalui perintah git prune, object yang tidak memiliki incoming pointers akan dihapus
29. Git fsck
Untuk membuat pengecekan keseluruhan dari file system git, gunakan perintah git fsck
30. Git rebase
Perintah ini digunakan untuk menerapkan ulang commit di branch yang lain