# lab5web

## Nama : Aan Fadillah Putra
## Nim : 312210327
## Kelas : TI.22.A3

# Praktikum 5 java script

1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama ```lab5_javascript.```
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
4. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org

### Praktikum

Buat dokumen html lab5_javascript.html
    <html>
    
    <head>
        <title>Mengenal Javascript</title>
    </head>
    
    <body>
        <h1>Pengenalan Javascript</h1>
        <h3>Contoh document.write dan console.log</h3>
        <script>
            document.write('Hello World !');
            console.log('Hello World !');
        </script>
    </body>
    
    </html>/

![aan1](https://github.com/aanfadillah/lab5web/assets/115763475/9adbea08-b0b9-4e26-8131-c3c5a568e6ed)

### JavaScript Dasar
#### Alert

<html>
    
    <head>
        <title>alert</title>
    </head>
    
    <body>
        <script language="javascript">
            window.alert("Ini merupakan pesan untuk anda");
        </script>
    </body>
    
    </html>

![aan2](https://github.com/aanfadillah/lab5web/assets/115763475/2cf62660-ead4-4c8f-b1db-ad0ce563cdaa)

#### Method
    <html>
    
    <head>
        <title>skrip Javascript</title>
    </head>
    
    <body>
        percobaan memakai Javascript:<br>
        <script lang="Javascript">
            document.write("selamat mencoba javascript<br>");
            document.write("Semoga sukses !");
        </script>
    </body>
    
    </html>
    
 ![aan3](https://github.com/aanfadillah/lab5web/assets/115763475/63631f21-4821-4e29-b587-5756d28feee3)


    #### Prompt
    <html>
        <head>
            <title>Pemasukan Data</title>
        </head>
        <body>
            <script lang="javascript">
                let nama = prompt("Siapa nama anda ?", "Masukan nama anda");
                document.write('hai, ' + nama);
            </script>
        </body>
    </html>

![aan4](https://github.com/aanfadillah/lab5web/assets/115763475/ce5f71e0-ae8b-4c71-875c-ae2c3c9cd9a9)

![aan5](https://github.com/aanfadillah/lab5web/assets/115763475/df98d3fa-3a8c-470d-8499-7dc5edb341ed)

#### Fungsi 
    <html>
    
    <head>
        <title>contoh program javascript</title>
        <script lang="javascript">
            function message() {
                alert("Memanggil javascript lewat body onload")
            }
        </script>
    </head>
    
    <body onload="message()"></body>
    
    </html>

![aan6](https://github.com/aanfadillah/lab5web/assets/115763475/2053fdfe-6b2d-4d30-81c1-cb82e86d9621)


#### Operasi Aritmatika
    <html>
        <head>
            <title>contoh program javascript</title>
            <script language="javascript">
                function test (a, b){
                    document.write(`<br> perkalian : ${a} * ${b} <br>`);
                    document.write(a*b);
                    document.write(`<br> pembagian : ${a}/${b} <br>`);
                    document.write(a/b);
                    document.write(`<br> penjumlahan : ${a} + ${b} <br>`);
                    document.write(a+b);
                    document.write(`<br> pengurangan : ${a} - ${b} <br>`);
                    document.write(a-b);
                    document.write(`<br> modulus : ${a} % ${b} <br>`)
                    document.write(a%b)
                }
            </script>
        </head>
        <body>
            <input type="button" value="arithmetic" onclick="test(4, 2)">
        </body>
    </html>

![aan7](https://github.com/aanfadillah/lab5web/assets/115763475/40daeddd-d643-48fa-ab8e-c953fd794c82)
![aan8](https://github.com/aanfadillah/lab5web/assets/115763475/3a1d5905-14e6-47ed-81bb-7012163a1c01)


#### If Else 
    <html>
    
    <head>
        <title>contoh if-else</title>
    </head>
    
    <body>
        <script lang="javascript">
            let nilai = prompt("nilai (0-100): ", 0);
            let hasil = "";
            if (nilai >= 60) {
                hasil = "lulus";
            } else {
                hasil = "tidak lulus";
            }
            document.write(`hasil: ${hasil}`);
        </script>
    </body>
    
    </html>
![aan9](https://github.com/aanfadillah/lab5web/assets/115763475/4f912cec-9b5f-449c-8509-0a48133eacd2)
![aan10](https://github.com/aanfadillah/lab5web/assets/115763475/21394a52-b9bc-4a46-a198-ee6a2c27e02f)
![aan11](https://github.com/aanfadillah/lab5web/assets/115763475/ddb07957-0926-424f-86b8-83bcffc33442)
![aan12](https://github.com/aanfadillah/lab5web/assets/115763475/f1a818b8-547d-4567-a07a-b80b5edd86f2)


#### Switch
    <html>
    
    <head>
        <title>contoh program javascript</title>
        <script lang="javascript">
            function test() {
                let num = window.prompt("Input 1-5")
                switch (num) {
                    case "1":
                        document.write("bilangan satu");
                        break;
                    case "2":
                        document.write("bilangan dua");
                        break;
                    case "3":
                        document.write("bilangan tiga");
                        break;
                    case "4":
                        document.write("bilangan empat");
                        break;
                    case "5":
                        document.write("bilangan lima");
                        break;
                    default:
                        document.write(`bilangan ${num} tidak termasuk`)
                        break;
                }
            }
        </script>
    </head>
    <body>
        <input type="button" value="switch" onclick="test()">
    </body>
    
    </html>
    
![aan13](https://github.com/aanfadillah/lab5web/assets/115763475/e74a78ba-6859-48a1-b4fd-fa876df40ff7)
![aan14](https://github.com/aanfadillah/lab5web/assets/115763475/e09f6873-7c3a-4d5b-909e-199c5f33aa2f)
![aan15](https://github.com/aanfadillah/lab5web/assets/115763475/61a1f7b6-9108-4337-abf9-837f8d46408b)

#### Form Input
    <html>
    
    <head>
        <title>Form Input</title>
        <script lang="javascript">
            function test() {
                let val = document.kirim.T1.value
                if (val % 2 === 0) {
                    document.kirim.T2.value = "bilangan genap"
                } else {
                    document.kirim.T2.value = "bilangan ganjil"
                }
            }
        </script>
    </head>
    
    <body>
        <form method="post" name="kirim">
            <p>
                BIL <input type="text" name="T1" size="20" /> MERUPAKAN BIL
                <input type="text" name="T2" size="20" />
            </p>
            <p><input type="button" value="TEBAK" name="B1" onclick="test()" /></p>
        </form>
    </body>
    
    </html>

![aan16](https://github.com/aanfadillah/lab5web/assets/115763475/d6ab460c-e24c-4d0d-bf45-64f6c99584e7)


#### Form Button
    <html>
    
    <head>
        <title>Form Input</title>
        <script lang="javascript">
            function test() {
                let val = document.kirim.T1.value
                if (val % 2 === 0) {
                    document.kirim.T2.value = "bilangan genap"
                } else {
                    document.kirim.T2.value = "bilangan ganjil"
                }
            }
        </script>
    </head>
    
    <body>
        <form method="post" name="kirim">
            <p>
                BIL <input type="text" name="T1" size="20" /> MERUPAKAN BIL
                <input type="text" name="T2" size="20" />
            </p>
            <p><input type="button" value="TEBAK" name="B1" onclick="test()" /></p>
        </form>
    </body>
    
    </html>
    
![aan17](https://github.com/aanfadillah/lab5web/assets/115763475/5a482d11-fa98-42d9-b0f1-06dbe51b133f)
![aan18](https://github.com/aanfadillah/lab5web/assets/115763475/9f4cef46-2cd4-458f-97ca-58bd88897620)
![aan19](https://github.com/aanfadillah/lab5web/assets/115763475/98c63ae6-126b-4ff6-9409-db73ac86174d)


### HTML DOM
Pilihan checkbox yang akan menghasilkan perhitungan otomatis

    <html>
    
    <head>
        <title>Daftar Menu</title>
        <script>
            function hitung(ele) {
                let total = document.getElementById("total").value;
                total = total ? parseInt(total) : 0;
                let harga = 0;
    
                if (ele.checked) {
                    harga = ele.value;
                    total += parseInt(harga);
                } else {
                    harga = ele.value;
                    if (total > 0) total -= parseInt(harga);
                }
    
                document.getElementById("total").value = total;
            }
        </script>
    </head>
    
    <body>
        <h1>Daftar Menu Makanan</h1>
        <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);" />
            Burger Rp 15.000</label><br />
        <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);" />
            Sosis bakar Rp 5000</label><br />
        <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);" />
            Spaghetti Rp 10.⁰00</label>
        <hr />
        <strong>Total Bayar: Rp <input type="text" id="total" /></strong>
    </body>
    
    </html>

![aan20](https://github.com/aanfadillah/lab5web/assets/115763475/d6227620-2589-4fa9-8979-0a80fc0f5732)
![aan21](https://github.com/aanfadillah/lab5web/assets/115763475/2a881559-f757-479b-af2a-b0502264e12a)
![aan22](https://github.com/aanfadillah/lab5web/assets/115763475/1ea8fd98-5617-4b8b-8229-c1ba4f529f03)


## Tugas
### 1. Buat script untuk melakukan validasi pada isian form.
- <a href="https://github.com/aanfadillah/Praktikum-PemogramanWeb/blob/main/Lab5Web/lab5_javascript/tugas.html">HTML</a> & <a href="https://github.com/aanfadillah/Praktikum-PemogramanWeb/blob/main/Lab5Web/lab5_javascript/css/style.css">CSS</a>

![aan23](https://github.com/aanfadillah/lab5web/assets/115763475/a7701857-1cce-4b3b-be96-6c17b56e9473)
![aan24](https://github.com/aanfadillah/lab5web/assets/115763475/6c3b824a-7f6c-4a12-beca-977fec3e0853)

