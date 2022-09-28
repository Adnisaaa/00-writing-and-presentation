# Week 1
### _Tugas Writing & Presentation test Week 1_ ✨


### **UNIX COMMAND LINE**
- **Shell**, penerjemah yang menghubungkan user dengan komputer. Shell merupakan program yang digunakan untuk memberikan perintah pada sistem/berkomunikasi.
- Command Line Interface **(CLI)**, merupakan sebuah program yang memungkinkan user mengetik perintah kepada sistem untuk menjalankan tugas tertentu.
- **Terminal**, merupakan tempat/aplikasi yang digunakan user untuk memberi perintah ke dalam sistem pada komputer. Dan terminal merupakan tempat shell berperan.
- **File System Structure**, merupakan struktur yang mengatur tersimpannya data ke dalam sistem.
- **Command**
    - `(pwd)`    : untuk melihat current working directory
    - `(ls/dir)` : untuk melihat isi sebuah directory 
    - `(cd)`     : untuk berpindah directory 
    - `(cat)`	: untuk melihat isi files 
    - `(mkdir)`	: untuk membuat folder/direktori 
    - `(touch)`  : untuk membuat file
    - `(cp)`	    : untuk menyalin file & direktori 
    - `(mv)`	    : untuk memindahkan atau me-rename file dan direktori 
    - `(rm)`	    : untuk menghapus file & direktori

### **GIT & GITHUB DASAR**
- Kenapa harus menggunakan **Git & Github**?
    karena dapat digunakan sebagai Alat Perencanaan dan Pengembangan Non-Linear, platform ini memungkinkan programmer dalam mengubah kode secara otomatis. Hal tersebut dapat menghemat waktu bagi programmer untuk menyusun dan mengubah sebuah kode.
- **Git** -- merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project.
- **Github** -- merupakan layanan cloud yang berguna untuk menyimpan dan mengelola sebuah project yang dinamakan repository (repo git).
- **Perbedaan Git dengan Github**
   |No. |  Git | Github |
   | ------  | ------ | ------ |
   | 1 | Meng-install software di penyimpanan lokal | Host melalui layanan cloud |
   | 2 | Dikelola oleh The Linux Foundation | Diakuisisi oleh Microsoft pada 2018 |
   | 3 | Berfokus pada version control dan code sharing | Berfokus pada source code hosting terpusat |
   | 4 | Akses secara offline | Akses secara online |
   | 5 | Menyediakan desktop interface bernama “Git GUI” | Menggunakan nama desktop interface “GitHub Desktop” |
- **Alur kerja Git & Github**
    ```
    1. *git init
    	untuk membuat repository baru
    2. *git status
    	untuk  melacak perubahan dalam folder/project
    3. *git add .
    	untuk mencatat perubahan yg terlacak
    4. *git commit -m "keterangan"
    	untuk menambahkan pesan ketika checkout pada setiap perubahan
    5.  *git config --global user.email "adnisaaa@gmail.com"
    6. *git config --global user.name "adnisa sabina"
    7. *git log --oneline
    	untuk melihat perubahan keseluruhan [agar outputnya lebih singkat]
    8. *git remote add (URL)
    9. *git push -u origin main
        //atau..
       *git push --set-upstream origin master
    ```

### **HTML**
- **HTML** merupakan sebuah 'kerangka' dari sebuah website. Berfungsi untuk membangun tampilan website yang telah menerapkan metode semantik untuk memudahkan setiap pengembang dalam proses development dan maintenance.
- Macam-macam **tag** dalam HTML
    - `<p>` Opening Tag (tag pembuka)
    - `</p>` Closing Tag (tag penutup)
    - `<b></b>` tulisan tebal		
    - `<i></i>` tulisan miring		
    - `<a href = ""></a>` tulisan dengan link		
    - `<img src="" alt=""></img>` gambar
    - `<ul><li></li></ul>` list	
    - dsb..
- Contoh **HTML yang sederhana**
    ```
    <html>
	    <head>
	        <title>Perkenalan HTML</title>
	    </head>
	    <body>
	        <h1>Hello World!</h1>
	    </body>
	</html> 
    ```
- **Semantic HTML**
    merupakan elemen atau tag yang memiliki sebuah arti, elemen semantik dengan jelas menjelaskan langsung artinya untuk browser dan pengembang.
    - `<h1>` hingga `<h6>` 
    - `<ul><li></li></ul>`
    - `<form>`, `<table>`, dan `<article>`

### **CSS**
- **CSS** merupakan sebuah 'baju' , yang memberi warna dan layout pada website
- Cara **menyisipkan CSS ke dalam HTML**

    - inline Style: menambahkann CSS langsung pada atribut HTML.

    - internal CSS: menggunakan element/tag `<style>` untuk menyisipkan kode CSS. element/tag `<style>` diletakkan di dalam `element <head>`

    - eksternal CSS: menyisipkan code CSS dengan cara membuat file CSS terpisah, dan lalu menyambungkannya dengan file HTML dengan menggunakan element . Element tersebut diletakkan di dalam element.
			  Kita memiliki dua file: index.html untuk file HTML-nya dan styles.css untuk file CSS-nya.
- **Sintaks** -- Terdiri dari properti dengan value Property adalah jenis tampilan yang ingin di ubah.
- **Styling** CSS pada sebuah halaman HTML 

    - **Inline Style**
    ```
    <p style="color:red">Tulisan ini berwarna merah
    </p>
    ```
    - **Eksternal CSS**
    ```
    === file.html ===
    <!DOCTYPE html>
    <html>
    <head>
          <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <h1>This is a heading</h1>
        <p>This is a paragraph.</p>
    </body>
    </html>
    ```
    ```
    === styles.css ===
    body {
      background-color: powderblue;
    }
    h1 {
      color: blue;
    }
    p {
      color: red;
    }
    ```

    - **Internal CSS**
    ```
    <!DOCTYPE html>
    <html>
    <head>
        <style>
            body {background-color: powderblue;}
            h1   {color: blue;}
            p    {color: red;}
        </style>
    </head>
    <body>
        <h1>This is a heading</h1>
        <p>This is a paragraph.</p>
    </body>
    </html>
    ```
- Metode **Responsive Web Design** -- merupakan tampilan website yang bisa menyesuaikan device pengguna. misalnya seperti menyesuaikan ukuran layar pengguna, mulai dari user interface, image, font, video akan menyesuaikan dengan resolusi device pengguna.
- **Flexbox** -- digunakan untuk mengatur elemen di suatu halaman web

### **ALGORITMA**
- **Algoritma** merupakan  urutan langkah logis tertentu untuk memecahkan suatu masalah
- **Struktur Data** merupakan cara mengumpulkan dan mengatur data sedemikian rupa sehingga kita dapat melakukan operasi pada sebuah data dengan cara yang efektif.
- Manfaat dari algoritma dan Struktur Data
    - Mempermudah kita untuk pembuatan program sehingga cepat terselesaikan.
	- Masalah terselesaikan secara sistematis.
- Algoritma sederhana **Hitung Luas Segitiga**
    ```
    1. Mulai
    2. Deklarasi variabel luas (L), alas (a) dan tinggi (t) segitiga
    3. Input nilai alas (a) dan nilai tinggi (t) segitiga
    4. Proses hitung luas (L) segitiga
    5. Tampilkan hasil luas (L) segitiga
    6. Selesai
    ```
- **Pseudocode** merupakan sebuah cara penulisan program yang informal dan dapat dibuat dengan kaidah yang ditentukan sendiri.
- Pseudocode  **Hitung Luas Segitiga**
    ```
    program hitung_luas_segitiga

    deklarasi
    var luas,alas,tinggi:integer;

    algoritma:
    alas <– 25;
    tinggi <– 30;

    luas <– 1/2 * alas * tinggi

    write(luas)
    ```
- **Big O Notation** -- adalah bahasa yang digunakan untuk berbicara tentang berapa lama suatu algoritma berjalan (kompleksitas waktu) atau berapa banyak memori yang digunakan oleh suatu algoritma (kompleksitas ruang).
    - `O (log n)`, juga dikenal dengan log time. Contoh: binary search
    - `O (n)`, juga dikenal dengan linear time. Contoh: simple search
    - `O (n * log n)`. Contoh: quicksort
    - `O (n²)`. Contoh: selection sort
    - `O (n!)`. Contoh: traveling salesmas problem

### **JAVASCRIPT**
- Javascript adalah bahasa pemograman yang sangat powerful yang digunakan untuk logic pada sebuah website dan dapat membuat **website menjadi interaktif** dan dinamis
- Javascript **dijalankan melalui browser** pada device setiap user. Seperti Google Chrome, Mozilla Firefox, Microsoft Edge, safari, dsb.
- **Tipe Data**
    - `number`	: tipe data yang mengandung semua angka termasuk angka desimal.
    - `string`	:  grup karakter yang ada pada keyboard laptop/PC kita yaitu letters (huruf), number (angka), spaces (spasi), symbol, dan lainnya.
    - `boolean`	: tipe data yang hanya mempunyai 2 buah nilai, yaitu TRUE (benar) or FALSE (salah).
    - `null`		: tipe data yang diartikan bahwa sebuah variable/data tidak memiliki nilai.
    - `undefined`	: tipe data yang merepresentasikan varibel/data yang tidak memiliki nilai.
    - `object`	: dapat menyimpan data dengan tipe data apapun (number, string, boolean, dan lainnya). Tipe data object mempunyai key dan value.
- **Operator**
	- Assignment Operator (`=`)
	- Mathematical Assignment Operator (`+=`, `-=`, `*=`, `/=`)
	- Increment (`++`) dan Decrement (`--`)
	- Arithmetic operator adalah operator yang melibatkan operasi matematika.
    - 	Tambah (`+`), Kurang (`-`), Perkalian (`*`), Pembagian (`/`), Modulus (`%`)
	- Comparison Operator
        - Lebih kecil dari : `<`
        - Lebih besar dari: `>`
        - Lebih kecil atau sama dengan: `<=`
        - Lebih besar atau sama dengan: `>=`
        - Sama dengan: `===`
        - Tidak sama dengan: `!==`
	- Logical Operator
        - AND operator : `&&`
        - OR operator: `||`
        - NOT operator: `!`
- Membedakan **control flow** (conditional dan looping)
    - **Conditional**, digunakan saat dibutuhkan percabangan kasus. Komputer akan melakukan suatu tindakan jika suatu kondisi terpenuhi.

	    contoh:

        ```
	    Jika hari ini tidak hujan, 
        maka Bob pergi ke pasar,
        jika tidak
        maka Bob dirumah aja.
	    	`IF` "bright"
	    	`DO` "go to the market"
	    	`ELSE`
	    	`DO` "stay at home"
        
    - **Looping**, dimana komputer dapat melakukan sebuah proses yang sama berulang-ulang.

	    contoh:
        ```
	    Jika membutuhkan perulangan dalam kasus tertentu, kita bisa menggunakan Looping. Misalnya menampilkan angka dari 1 sampai 5:
		
		for (let i = 1; i <= 5; i++) {
  		text += "The number is " + i + "<br>";
		}
        ```
