# Lab3Web

# Praktikum 3

# Pemograman WEB

~~~
Nama  : Isnaini Rizkyana
NIM   : 311910254
Kelas : TI.19.C1
~~~

## Langkah-langkah Praktikum
Persiapan membuat dokumen HTML dengan nama file lab3_list.html seperti berikut.
~~~
<!DOCTYPE html>
<html lang="en">
<head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>HTML Lanjutan</title>
 </head>
 <body>
    <header>
    <h1>Membuat List</h1>
    </header>
 </body>
 </html>
~~~
![lab3_list](https://user-images.githubusercontent.com/81541764/115008327-2f141500-9ed5-11eb-9980-602bbe533306.JPG)


## Membuat Ordered List
Kemudian tambahkan kode untuk membuat Ordered List seperti berikut.
~~~
<section id="order-list">
    <h2>Ordered List</h2>
      <ol>
          <li>Pemrograman Web</li>
          <li>Sistem Informasi</li>
          <li>Basis Data 2</li>
     </ol>
</section>
~~~

![Membuat Ordered List](https://user-images.githubusercontent.com/81541764/115005044-a8116d80-9ed1-11eb-9992-a5f581365b39.JPG)

## Membuat Unorderd List
Kemudian tambakan kode untuk membuat *Unordered List*, setelah deklarasi ordered list pada section unordered-list, seperti berikut.
~~~
<section id="unorder-list">
    <h2>Unordered List</h2>
      <ul type="square">
          <li>Jaringan Komputer</li>
          <li>Struktur Data</li>
          <li>Algoritma &amp; Pemrograman</li>
       </ul>
</section>
~~~
![Membuat Unordered List](https://user-images.githubusercontent.com/81541764/115006689-61247780-9ed3-11eb-9040-b8278b0cdf2c.JPG)

## Membuat Description List
Kemudian tambahkan kode untuk membuat description list setelah deklarasi unorderd-list.
~~~
<section id="unorder-list">
      <h2>Description List</h2>
      <dl>
          <dt>Fakultas Teknik</dt>
            <dd>Teknik Industri</dd>
            <dd>Teknik Informatika</dd>
            <dd>Teknik Lingkungan</dd>
          <dt>Fakultas Ekonomi dan Bisnis</dt>
            <dd>Akuntansi</dd>
            <dd>Manajemen</dd>
            <dd>Bisnis Digital</dd>
      </dl>
 </section>
~~~

![Membuat Description List](https://user-images.githubusercontent.com/81541764/115007229-f6c00700-9ed3-11eb-9d2d-50df74a2ce21.JPG)

Selanjutnya lakukan eksperimen lain terkait list dan penggunaan atribut type pada list.

## Membuat Tabel
Buat file baru dengan nama lab3_tabel.html seperti berikut.
~~~
<!DOCTYPE html>
<html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>HTML Lanjutan</title>
    </head>
    <body>
       <header>
            <h1>Membuat Table</h1>
       </header>
    </body>
 </html>
~~~
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
~~~
<table border="1" cellpadding="4" cellspacing="0">
<thead>
      <tr>
        <th>No.</th>
        <th>Fakultas</th>
        <th>Program Studi</th>
      </tr>
</thead>
<tbody>
      <tr>
         <td>1.</td>
         <td>Teknik</td>
         <td>Teknik Informatika</td>
      </tr>
      <tr>
         <td>2.</td>
         <td>Teknik</td>
         <td>Teknik Industri</td>
      </tr>
      <tr>
          <td>3.</td>
          <td>Teknik</td>
          <td>Teknik Lingkungan</td>
      </tr>
</tbody>
</table>
~~~

![Membuat tabel1](https://user-images.githubusercontent.com/81541764/115008105-ee1c0080-9ed4-11eb-82ff-7a206e88d714.JPG)

## Mengatur Margin dan Padding
Untuk mengatur margin dan padding pada cel data, tambahkan atribut cellpadding dan cellspacing pada tag table.
~~~
<table border="1" cellpadding="4" cellspacing="0">
~~~
![Membuat tabel1](https://user-images.githubusercontent.com/81541764/115008814-c9745880-9ed5-11eb-9b07-bb803ae543c4.JPG)

## Menggabungkan Sel Data
Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara horizontal).
~~~
<table border="1" cellpadding="6" cellspacing="0">
<thead>
      <tr>
          <th>No.</th>
          <th>Fakultas</th>
          <th>Program Studi</th>
      </tr>
</thead>
<tbody>
      <tr>
          <td>1.</td>
          <td rowspan="3">Teknik</td>
          <td>Teknik Informatika</td>
      </tr>
      <tr>
          <td>2.</td>
          <td>Teknik Industri</td>
      </tr>
      <tr>
          <td>3.</td>
          <td>Teknik Lingkungan</td>
      </tr>
</tbody>
</table>
~~~
![Menggabungkan Sel Data](https://user-images.githubusercontent.com/81541764/115009361-6c2cd700-9ed6-11eb-83c9-e30965b6af5d.JPG)

## Membuat Form
Buat file baru dengan nama lab3_form.html seperti berikut.
~~~
<!DOCTYPE html>
<html lang="en">
<head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>HTML Lanjutan</title>
</head>
<body>
      <header>
              <h1>Membuat Form</h1>
      </header>
</body>
</html>
~~~
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
~~~
 <form action="proses.php" method="post">
    <fieldset>
            <legend>Data Pelanggan</legend>
        <p>
            <label for="nama">Nama</label>
            <input type="text" id="nama" name="nama">
        </p>
        <p>
            <label for="alamat">Alamat</label>
            <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
        </p>
        <p>
            <label>Jenis Kelamin</label>
            <input id="jk_l" type="radio" name="kelamin" value="L" />
                <label for="jk_l">Laki-laki</label>
            <input id="jk_p" type="radio" name="kelamin" value="P" />
                <label for="jk_p">Perempuan</label>
        </p>
        <p>
            <input type="submit" value="Login">
        </p>
    </fieldset>
    </form>
~~~
![Membuat Form](https://user-images.githubusercontent.com/81541764/115013341-1a3a8000-9edb-11eb-8529-65c1cd7acfe3.JPG)

## Menabahkan Style pada Form
Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut.
~~~
<style>
      form p > label {
            display: inline-block;
            width: 100px;
      }
      form input[type="text"], form textarea {
            border: 1px solid #197a43;
      }
      form input[type="submit"] {
            border: 1px solid #197a43;
            background-color: #197a43; 
            color: #ffffff;
            font-weight: bold;
            padding: 5px 15px;
      }
</style>
~~~

![Menambahkan Style pada Form](https://user-images.githubusercontent.com/81541764/115013704-96cd5e80-9edb-11eb-88cd-aa9c9ae7e0ce.JPG)

# Pertanyaan dan Tugas
1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.

![Membuat Dropdown menu dan listbox](https://user-images.githubusercontent.com/81541764/115013768-ab115b80-9edb-11eb-976b-f065bfad1a25.JPG)
