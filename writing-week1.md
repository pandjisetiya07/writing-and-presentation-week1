# TUGAS WRITING-AND_PRESENTATION-WEEK1

__PANDJI SETIYA BUDHI ARTHA__ -- _Tugas writing minggu pertama_

| __No__ | __Materi untuk minggu pertama__ | 
|----|-----------------------------|
|  1 | Terminal Basic              |
|  2 | Git & Git Hub               |
|  3 | HTML Dasar                  |
|  4 | CSS Dasar                   |
|  5 | Algritma dan Pseudoceode    |
 
---------------------------------------------------------------
1. __Terminal Basic__<br>
    Sebuah Command untuk mengntrol file, membuat file, membuat folder, membuat akses, merubah akses ataupun membaca, membuat, merubah file, dan masih banyak lagi fungsi yang lainnya. Adapun perintah umum terminal basic dapat dilihat pada tabel di bawah ini :<br>

| __No__ | __Command__ | __Keterangan__ |
|--------|-------------|----------------|
|    1   | ls          | Melihat __All Folder__ di dalam directory |
|    2   | cd          | Masuk kedalam __Folder Tertentu__ |
|    3   | cd D/E:     | Masuk Directory __Local Disk(D)/(E)__ |
|    4   | cd ..       | Untuk __Keluar__ dari folder |
|    5   | touch       | Membuat __File Baru__ pada OS Linux dan Mac |
|    6   | ni          | Membuat __File Baru__ pada OS windows |
|    7   | cp          | Untuk __Copy File__  di dalam satu folder / antar folder lainnya|
|    8   | cp -r       | Untuk __Mengcopy Suatu Folder__ |
|    9   | mv          | __Memindahkan File / Folder__ ke dalam directory baru, apabila file atau folder mengandung spasi dapat menggunakan __"nama file/folder"__ |
|   10   | rm & rm -r  | Untuk __Menghapus file & folder__ apabila ingin menghapus lebih dari satu file bisa menggunakan tanda __( , )__ |
|   11   | mkdir       | Untuk membuat __Folder baru__ |
|   12   | pwd         | Untuk __Menampilkan sedang posisi saat ini__ |
|   13   | clear       | Menghapus semua command yang ada |

-----------------------------------------------------------------------------
2. __GIT & GITHUB__
* GIT - berfungsi sebagai _Version Control System_ yang tugasnya __Mencatat__ setiap __perubahan pada File__. Pada suatu proyek baik __individu maupun tim__, GIT biasanya digunakan oleh programmer sebagai tempat __menyimpan__ file.
<br>

- __Mengecek instalasi GIT__<br>
![git version](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/git%20version.PNG?raw=true)<br>
Apa bila muncul seperti gambar di atas maka __Instalasi Berhasil__<br>

- __Setup Awal__<br>
Untuk setup awal bisa menggunakan code <br>__git config --global user.name "Nama Kalian"__ <br> __git config --global user.email "Alamat Email"__<br>

- __Mengecek Setup Berhasil__<br>
Ketikkan command dibawah ini untuk mengecek setup berhasil atau tidak.
![git list](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/git%20list.PNG?raw=true)<br> 
Apa Bila berhasil maka akan muncul seperti gambar di bawah.<br>
![berhasil setup](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/berhasil%20setup.PNG?raw=true)<br>

- __Daftar Command GIT yang Sering digunakan__<br>

| __No__ | __Command__ | __Keterangan__ |
|--------|-------------|----------------|
|   1    | git init    | Untuk _Install_ git dalam directory kerja kita | 
|   2    | git add & git add . | __Menambakan 1 file__ ke dalam staging area dan masih perlu di commit, bila ingin menambahkan __Seluruh File__ maka tambahkan  __.__ | 
|   3    | git commit -m "tambahkan pesan" | Untuk __Save Perubahan__ pada _Version Control_ serta menambahkan _checkpoint_ |
|   4    | git log     | Melihat __History__ / kumupalan __Commit__ yang telah dibuat |
|   5    | git revert  | Kembali pada _Checkpoin_ yang diinginkan tanpa __menghapus__ commid sesudahnya |
|   6    | git reset   | Kembali pada _Checkpoin_ yang diinginkan dan __menghapus__ commit sesudahnya | 
|   7    | git branch   | Biasanya digunakan apabila mengerjakan proyek dalam bentuk tim, dan tidak boleh mengganggu __Branch 'Master'__ yang ada |
|   8    | git branch -d | Digunakan untuk __Menghapus__ Branch yang ada |
|   9    | git checkout | Untuk __Pindah Branch__ yang di inginkan |
|  10    | git checkout -b | __Membuat__ Branch dan langsung __pindah__ ke branch yang baru dibuat |
|  11    | Git status   | Untuk melihat apakah file / folder yang telah di edit, dan sudah di __git add__ namun belum di __git commit__ atau pun yang sudah di commit |

---------------------------------------------------------------

3. __HTML DASAR__ <br>

- Apa itu HTML ?<br>
HTML adalah suatu kerangka dari sebuah website yang digunkan untuk __menampilkan konten pada browser__. Konten yang dapat di tampilkan seperti __TEXT, IMAGE, VIDEO, LINK, dan masih banyak lagi__<br>

- Dasar - dasar HTML <br>
[ x ] Membuat file HTML --> buat file baru dengan extensi __.html / .htm__