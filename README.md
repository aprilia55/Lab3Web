# Praktikum 3 — Membuat List, Table, dan Form  
**Nama:** Aprilia Putri  
**NIM:** _(isi NIM kamu)_  
**Kelas:** _(isi kelas kamu)_  
**Mata Kuliah:** Pemrograman Web  

---

## 🎯 Tujuan Praktikum
1. Mahasiswa memahami struktur dasar pembuatan **List (daftar)** di HTML.  
2. Mahasiswa memahami struktur dasar pembuatan **Tabel (table)** di HTML.  
3. Mahasiswa memahami tag-tag dasar untuk membuat **Form (formulir)**.  
4. Mahasiswa mampu mengimplementasikan penggunaan **CSS** pada List, Table, dan Form.

---

## Langkah 1 — Membuat List
File pertama: **lab3_list.html**  
List digunakan untuk menampilkan data berbentuk daftar.

### Ordered List
```html
<ol type="A">
  <li>Pemrograman Web</li>
  <li>Sistem Informasi</li>
  <li>Basis Data 2</li>
</ol>

<dl>
  <dt>Fakultas Teknik</dt>
  <dd>Teknik Informatika</dd>
  <dd>Teknik Industri</dd>
  <dd>Teknik Lingkungan</dd>
  <dt>Fakultas Ekonomi</dt>
  <dd>Manajemen</dd>
  <dd>Akuntansi</dd>
</dl>


<ul type="square">
  <li>Jaringan Komputer</li>
  <li>Struktur Data</li>
  <li>Algoritma &amp; Pemrograman</li>
</ul>
```
## Hasil Praktek

![tampilan hasil]()

## 2. Membuat Table

Saya membuat file `lab3_tabel.html` untuk menampilkan data dalam bentuk tabel dengan menggunakan tag `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, dan `<td>`.

Kode Program:

```html
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

```

## Hasil Praktek 

![foto]()

## 3. Membuat Form

Saya membuat file `lab3_form.html` untuk membuat form data pelanggan dengan elemen-elemen:

`<form>` → pembungkus form.

`<fieldset>` → memberi batas (kotak) di dalam form.

`<legend>` → judul form.

`<label>` → teks penjelas kolom.

`<input>` dan <textarea> → kolom input.

```html

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
      <input id="jk_l" type="radio" name="kelamin" value="L">
      <label for="jk_l">Laki-laki</label>
      <input id="jk_p" type="radio" name="kelamin" value="P">
      <label for="jk_p">Perempuan</label>
    </p>

    <p>
      <input type="submit" value="Login">
    </p>
  </fieldset>
</form>

```

## Hasil Praktek
![foto]()

## 4. Menambahkan CSS pada Form

Saya menambahkan CSS agar tampilan form terlihat lebih rapi dan menarik.
CSS ditulis di dalam tag `<style>` di bagian `<head>`.

```html

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
  color: white;
  padding: 5px 15px;
  font-weight: bold;
}
```
## Hasil Praktek
![foto]()


