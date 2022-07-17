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
# 1. __Terminal Basic__<br>
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
# 2. __GIT & GITHUB__
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

# 3. __HTML DASAR__ <br>

- Apa itu HTML ?<br>
HTML adalah suatu kerangka dari sebuah website yang digunkan untuk __menampilkan konten pada browser__. Konten yang dapat di tampilkan seperti __TEXT, IMAGE, VIDEO, LINK, dan masih banyak lagi__<br>

- Dasar - dasar HTML <br>
[ x ] __Membuat file HTML__ --> buat file baru dengan extensi __.html / .htm__ <br>
[ x ] __STRUKTUR HTML__ <br>
![dasar HTML](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/dasar%20html.PNG?raw=true) <br>
Pada gambar diatas struktur HTML terdiri dari __HEAD__ dan __BODY__ . Yang nantinya akan muncul pada _brwoser_ yaitu yang berada di struktur __BODY HTML__. <br>

---------------------------------------------------------------
[ x ] __HTML ANATOMY & HTML ELEMENT__ <br>
![html anatomy](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/html%20anatomy.png?raw=true) <br>
Gambar di atas mendefinisakan __html element__ terdiri dari : __element, tag buka, tag tutup, dan content__ . contoh lainnya seperti gambar dibawah ini : <br>
![html anatomy 2](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/html%20anatomy%202.png?raw=true) <br>

---------------------------------------------------------------
[ x ] __HTML ATTRIBUT__ <br>
ATTRIBUT adalah __properties__ dari sebuah HTML dan hampir semua HTML __memiliki element attribut__. seperti pada contoh gambar dibawah ini : <br>
![html atribut](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/html%20atribut.PNG?raw=true) <br>
Pada contoh di atas terdapat beberapa contoh __attribut__ yang kerap digunakan oleh _programmer_ yaitu __id, class, src, href__. Namun Attribut yang sering digunakan dalam HTML adalah attribut __class__. <br>

--------------------------------------------------------------
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

---------------------------------------------------------------
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

---------------------------------------------------------------
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

---------------------------------------------------------------
- __Text area__  merupakan elemen yang dapat menyimpan kata dan __dapat diperluas__ jika pengguna memasukkan __lebih banyak text__ sehingga dapat dimasukkan pada elemen text area. <br>
```
<!DOCTYPE html>
<html>
<body>

<h2>Styling Textarea</h2>

<p>Use CSS to change the size of the textarea:</p>

<form action="/action_page.php">
  <textarea name="message" style="width:300px; height:200px;">The cat was playing in the garden.</textarea>
  <br>
  <input type="submit">
</form>

</body>
</html>
```
__Hasilnya akan seperti gambar di bawah ini__ <br>
![html text area](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/html%20text%20area.PNG?raw=true) <br>

------------------------------------------------------------

- __Email__ Yaitu mendefinisikan bidang untuk alamat email.
Nilai input divalidasi secara otomatis untuk memastikan bahwa itu adalah alamat email yang diformat dengan benar,
berikut contoh penulisan nya : <br>
![html email](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/html%20email.PNG?raw=true)

---------------------------------------------------------------
- __Password__ Akan mendefinisikan bidang kata sandi (karakter disamarkan), berikut contoh penulisan nya : <br>
![hrml password](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/html%20password.PNG?raw=true)

---------------------------------------------------------------
-  __Button__ Elemen button ini biasa digunakan untuk membuat sebuah tombol, sehingga pengguna dapat melakukan suatu aksi, berikut contoh nya : <br>
![html button](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/html%20button.jpg?raw=true)

---------------------------------------------------------------
# 4. __CSS DASAR__ <br> 
Setelah mempelajari __HTML Dasar__ sekrang kita akan masuk pada materi __CSS__ yang dapat di lihat pada tabel di bawah ini : <br>

| __No__ | __Materi__ | __Penjelasan__ | __Gambar__ |
|--------|------------|----------------|------------|
|   1    | Apa Itu Css | Adalah bahasa yang digunakan untuk mendesain halaman website. Dengan CSS, kita bisa mengubah warna, menggunakan font custom, editing text format, mengatur tata letak, dan lainnya. | - |
|   2    | Struktur CSS | Struktur CSS Mempunyai 3 bagian penting yaitu : <br> __1. Element html / selector__ -> adalah kata __kunci__ untuk menentukan element html yang akan di beri __style__ <br> __2. Properti__ -> merupakan atribut atau aturan yang akan diterapkan oleh elemen yang dipilih (selektor). <br> __3. Value__ -> isi dari _Properti_ perlakuan apa yang ingin kita berikan pada HTML yang kita _selector_ | [contoh 1 struktur css](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/struktur%20css.png?raw=true) <br> [ contoh 2 struktur css](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/struktur%20css%202.PNG?raw=true) |
|   3   | CSS Comment | Memberikan penjelasan terkait program yang di kerjakan dan __tidak akan dieksekusi oleh sistem__ hanya bisa dibaca oleh __programmer__ | [comment single css](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/comment%20single%20css.png?raw=true) <br> [comment multiple css](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/comment%20multiple%20css.png?raw=true) |
|   4   | Cara menggunakan CSS | Ada 3 cara menggunakan CSS <br> __1. Inline Style__ adalah sebuah kode CSS yang kita sematkan pada element apa pun di dalam body HTML, langsung menggunakan atribut _style_. <br> __2. Internal CSS__ Adalah menggunakan CSS internal. CSS internal adalah CSS yang diletakkan pada bagian ``<head>`` suatu halaman HTML. <br> __3. Eksternal CSS__ adalah kita membuat file tersendiri yang berekstensi __.css.__ Kemudian file tersebut kita hubungkan ke dalam halaman HTML menggunakan __tag ``<link>``.__ | 1. [Inline CSS](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/inline%20style%20CSS.png?raw=true) <br> 2. [Internal CSS](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/internal%20CSS.PNG?raw=true)<br> 3. [External CSS membuat file](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/external%20css.png?raw=true)<br> [pemanggilan CSS dalam HTML](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/external%20css%202.png?raw=true) |
|   5   | Tag Name CSS | Menggunakan tag HTML secara langsung pada CSS akan bersifat __global__ yang artinya __kita merubah satu tag maka semua isi dalam tag tersebut akan mengikuti__  | 1.[Code tag HTML](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/tag%20name%20css%20code%20html.png?raw=true) <br> 2. [tag name dalam file css](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/tag%20name%20css.png?raw=true) <br> 3. [hasil pada browser](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/hasil%20tag%20name%20css.png?raw=true) |
|   6   | Perbedaan ID Name dan Class Name CSS | 1.  __ID Name / ID  selector__ ini merupakan selector untuk menentukan bagian yang __hanya ada satu__ pada halaman. Jika ada dua, maka hanya bekerja pada bagian pertama saja. ID dituliskan dengan awalan __pagar/sharp/kers ('#')__. <br> 2. __Class Name / Class selector__ bisa dipanggil __berkali kali pada satu halaman.__ Selector ini ditulis dengan awalan __titik atau dot “.”__ pada css dan __class=“nama-class”__ pada HTML. | 1. [id name pada HTML](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/selector%20ID%20pada%20html.PNG?raw=true) <br> 2. [id name pada CSS](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/selector%20ID%20pada%20CSS.PNG?raw=true) <br> 3.[class pada HTML](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/selector%20CLASS%20pada%20HTML.PNG?raw=true) <br> 4. [class pada CSS](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/selector%20CLASS%20pada%20CSS.PNG?raw=true) |
|   7   | Multiple Selector | Mengefektifkan Code tanpa melakukannya berulang kaliseperti contoh dalam penggunaan _class_ di html. | Contoh : <br> 1.[Multiple selector pada HTML](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/multiple%20CSS%20pada%20HTML.PNG?raw=true) <br> 2. [Multiple selector pada file CSS](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/multiple%20CSS%20pada%20CSS.PNG?raw=true) <br> 3.[Hasil pada browser](https://github.com/pandjisetiya07/writing-and-presentation-week1/blob/main/img/multiple%20CSS%20pada%20browser.PNG?raw=true) | 

--------------------------------------------------------------------------------------

# 5. __Algritma dan Pseudoceode__ <br>
## __Apa itu Algotrima ?__ <br>
Algoritma adalah deskripsi berupa step-step yang dibutuhkan untuk menyelesaikan suatu masalah. <br>

## __Kualiatas Algoritma dapat dilihat dari 3 aspek yaitu :__
1. __Input dan output__ harus didefinisikan terlebih dahulu dengan tepat. <br>
2. Setiap step harus benar-benar __clear dan tidak ambigu__. <br>
3. Algoritma seharusnya tidak mengandung suatu code pada bahasa pemograman tertentu. Algoritma harus dibuat agar dapat digunakan dalam bahasa pemograman apapun.

## __Apa itu Pseudoceode?__
Pseudocode adalah menuliskan algoritma dengan umumnya bahasa inggris sebelum kita implementasikan ke bahasa pemograman tertentu.<br>

## __Panduan menulis pseudocode__
- Menggunakan HURUF BESAR pada kata kunci (key commands). <br>
__CONTOH: IF number is > 10 THEN …__ <br>
- 1 statement =  1 baris <br> 
- Gunakan indentasi <br>
- Please be specific <br>
- Tapi tetap simpel <br>
    


