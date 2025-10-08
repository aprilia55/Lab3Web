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
![tampilan hasil] ()

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




