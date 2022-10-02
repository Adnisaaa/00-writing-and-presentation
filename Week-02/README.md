# Week 2
## _Tugas Writing & Presentation test Week 2_ ✨


## **JAVASCRIPT DASAR**
### **Scope and Function**
- `Js Dasar-Scope`, merupakan konsep dalam flow data variabel. Scope juga bisa digunakan untuk menentukan suatu variabel bisa diakses atau tidak. Terdapat 3 tipe pada scope, diantaranya:
    - **Block scope** adalah code yang berada didalam curly braces { }. Berupa Conditional, function, ataupun looping.
    ```
    {
        var i = 7;
    }
    ```
    - **Local scope** adalah variabel yang dideklarasikan didalam blocks seperti function, conditional, dan looping. Sehingga variabel hanya bisa diakses didalam blocks saja. Tidak bisa diakses diluar blocks.
     ```
    function greeting(){
        let myName = "Adnisa"
        return myName
    }

    console.log(greeting()) //output: Adnisa
    console.log(myName)     //output: myName undefined
     ```
    - **Global scope** adalah variabel yang dapat diakses dimanapun dalam suatu file. Sehingga suatu variabel harus dideklarasikan diluar Blocks. 
    ```
    let myName = "Adnisa"
    function greeting(){
        return myName
    }

    console.log(myName)     //output: Adnisa
    ```

- `Js Dasar-Function`, merupakan sebuah blok kode dalam sebuah grup untuk menyelesaikan 1 task/1 fitur. Dan nantinya fitur tersebut bisa digunakan kembali.
    ```
    let i = myFunction(3, 2)

    function myFunction(a, b){
        return a * b
    }                       //output: 6
    ```

- `Errors and Debugging`, merupakan kondisi dimana kode pemrograman mungkin berisi kesalahan sintaks, atau kesalahan logis. Langkah mencari (dan memperbaiki) kesalahan dalam kode pemrograman disebut debugging.

&nbsp;

### **Data Type Built in Prototype & Method**

- Data Type -- dalam pemrograman, tipe data merupakan konsep yang penting. Untuk dapat beroperasi pada variabel, penting untuk mengetahui sesuatu tentang jenisnya.
- String
    
    String adalah tipe data dalam grup karakter yang ada pada keyboard laptop/PC kita yaitu letters (huruf), number (angka), spaces (spasi), symbol, dan lainnya.
- Number
    
    Number adalah tipe data yang mengandung semua angka termasuk angka desimal.
- Math

    Math bukan class dari objek seperti Number atau String. Math dapat kita definisikan sebagai **library javascript** yang digunakan untuk membuat suatu aplikasi yang mengandung / menggunakan banyak proses aritmatika didalamnya.
- Primitive & Non Primitive

    **Primitive** adalah tipe data yang hanya dapat menyimpan satu nilai pada satu waktu dan tidak dapat diubah menggunakan cara yang sama seperti tipe data non-primitif. Tipe data Primitif akan dianggap sama jika nilainya sama. Contohnya: `string`, `number`, `boolean`, `null`, `undefined`, dan `symbol`.

    **Non Primitive** adalah tipe data yang hanya dapat menyimpan lebih dari satu nilai pada satu waktu dan dapat diubah. Tipe data non-primitif akan dianggap berbeda meskipun nilainya sama dan dalam urutan yang sama. Contohnya: `array` dan `object`


### **DOM** (_document object model_)
- DOM bukan bagian dari Javascript melainkan sebuah web API untuk membangun website. Merupakan standar objek model untuk mengakses dan mengubah dokumen web, yang akan membentuk sebuah struktur pohon dan dapat pula memanipulasi tampilan web.

    Merepresentasikan sebuah halaman yang dimana struktur, style dan kontennya bisa diubah.
- Traversing, merujuk pada posisi elemen dalam tree elemen, apakah sebagai induk (parent) atau sebagai anak (child) atau setingkat (sibling) bagi elemen HTML lain.
    - getElementById()
    - getElementsByClassName()
    - getElementsByTagName()
    - querySelector()
    - querySelectorAll()
    - children()
    - parentElement()
    - closest()
    - nextElementSibling()
    - previousElementSibling()

&nbsp;
- Manipulation:
    1. innerHTML
        ```
        let app = document.getElementById("app")

        app.innerHTML = "<h1>Hallo, apa kabss</h1>" 
        ```
    2. innerText
        ```
        let app = document.getElementById("app")

        app.innerText = "Halo Dunia" 
        ```
    3. createElement()
        ```
        let p = document.createElement("p")

        p.innerText = "ini adalah paragraf"
        ```
    4. append()
        ```
        app.append(p)
        ```
    5. appendChild()
        ```
        let p2 = document.createElement("p")
        p2.innerText = "paragraf ke-2"

        app.appendChild(p2)
        ```
    6. remove
        ```
        let end = document.getElementById("end")

        end.remove()
        ```
    7. p.attributes
        ```
        let link = document.getElementsByClassName("link")[0]'
        console.log(link.attributes);
        ```
    8. p.style.color
        ```
            link.style.color = "red"
        ```
        &nbsp;
- Events, merupakan suatu interaksi yang user berikan kepada website, misalnya seperti: `click`, `submit`, `focus`, `blur`, `hover`, `change`, `scroll`, dsb.
