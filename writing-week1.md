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
[ x ] __Membuat file HTML__ --> buat file baru dengan extensi __.html / .htm__ <br>
[ x ] __STRUKTUR HTML__ <br>
![dasar HTML](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/dasar%20html.PNG?raw=true) <br>
Pada gambar diatas struktur HTML terdiri dari __HEAD__ dan __BODY__ . Yang nantinya akan muncul pada _brwoser_ yaitu yang berada di struktur __BODY HTML__. <br>
[ x ] __HTML ANATOMY & HTML ELEMENT__ <br>
![html anatomy](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/html%20anatomy.png?raw=true) <br>
Gambar di atas mendefinisakan __html element__ terdiri dari : __element, tag buka, tag tutup, dan content__ . contoh lainnya seperti gambar dibawah ini : <br>
![html anatomy 2](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/html%20anatomy%202.png?raw=true) <br>
[ x ] __HTML ATTRIBUT__ <br>
ATTRIBUT adalah __properties__ dari sebuah HTML dan hampir semua HTML __memiliki element attribut__. seperti pada contoh gambar dibawah ini : <br>
![html atribut](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/html%20atribut.PNG?raw=true) <br>
Pada contoh di atas terdapat beberapa contoh __attribut__ yang kerap digunakan oleh _programmer_ yaitu __id, class, src, href__. Namun Attribut yang sering digunakan dalam HTML adalah attribut __class__. <br>
[ x ] __HTML TABLE__ <br>
Salah satu elemen yang akan sering digunakan, elemen ini akan menampilkan tabel pada halaman browser kita, contoh penulisan code tabel di html : <br>
![html tabel](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/html%20tabel.png?raw=true) <br>
Pada gambar di atas terdapat beberapa tag yang berhubungan dengan table yaitu __``` <tabel>, <tr>, <th>, <td> ```__. <br>
- Tag __```<table>```__ digunakan untuk mendeklarasikan pembuka dan penutup table. <br>
- Tag __```<tr>```__ berfungsi untuk membuat baris pada tabel (table row). <br>
- Tag __```<th>```__ digunakan untuk mengelompokkan bagian header tabel.  <br>
- Tag __```<td>```__ digunakan untuk membuat kolom di dalam baris tabel di HTML sehingga akan membentuk sel (table data) <br>
Adapun tag lain sepeti __``<thead> <tbody> <tfoot>``__ <br>
- Tag __``<thead>``__ digunakan untuk mengelompokkan bagian header tabel. <br>
- Tag __``<tbody>``__ digunakan untuk mengelompokkan bagian konten atau body tabel.
- Tag __``<tfoot>``__ digunakan untuk mengelompokkan bagian footer dari tabel. <br>
[ x ] __HTML FORM__ <br>
Form merupakan bagian pada HTML yang dapat digunakan untuk membuat elemen Form pada halaman Web.
Elemen Form dapat terdiri dari __check box, radio button, text area, email, password, button dan lainnya__. berikut penjelasan dari setiap element Form :<br>
- __Checkbox__  : Digunakan ketika memerlukan form yang dapat memilih lebih dari satu pilihan contohnya. <br>

```
<!DOCTYPE html>
<html>
<body>

<h2>Checkboxes</h2>
<p>The <strong>input type="checkbox"</strong> defines a checkbox:</p>

<form action="/action_page.php">
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
  <label for="vehicle3"> I have a boat</label><br><br>
  <input type="submit" value="Submit">
</form> 

</body>
</html>
```
__Hasilnya akan seperti gambar di bawah ini__ <br>
![html form checkbox](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/html%20form%20checkbox.PNG?raw=true) <br>

- __Radio Button__ <br>
Radio Buttons digunakan ketika memerlukan form yang dapat memilih salah satu diantara beberapa pilihan. <br>

```
<!DOCTYPE html>
<html>
<body>

<h2>Radio Buttons</h2>

<p>Choose your favorite Web language:</p>

<form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label>
</form> 

</body>
</html>
```
__Hasilnya akan seperti gambar di bawah ini__ <br>
![html form radio botton](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/html%20form%20radio%20button.PNG?raw=true) <br>

- __Text area__  merupakan elemen yang dapat menyimpan kata dan __dapat diperluas__ jika pengguna memasukkan __lebih banyak text__ sehingga dapat dimasukkan pada elemen text area. <br>

