---
sidebar_position: 2
---

## deklarasi

Tahap pertama membuat variable adalah deklarasi, struktur deklarasi variable adalah dengan kata kunci **let** lalu diikuti nama variable, contoh:

```js
let nama // ini berhasil
let umur // ini berhasil
```

penulisan nama variable harus dimulai dengan huruf kecil seperti `nama`, jika terdiri dua kata atau lebih, kata berikutnya menggunakan huruf kapital, seperti `nama pak guru` menjadi `namaPakGuru`, nama variable juga tidak boleh dimulai dengan angka

```js
let namaIbuDosen // ini berhasil
let 3Nama // ini error
```

## assignment

Setelah deklarasi, kita akan melakukan assignment atau memasukkan data, caranya adalah dengan menambahkan `= <data yang ingin dimasukkan>` setelah deklarasi, contoh:

```js
let nama = 'titin' 
let umur = 22
let umur 22 // ini error karna tidak ada tanda =
```

Setelah memasukkan data, maka variable tersebut akan berisi data yang disediakan, nama akan berisi titin dan umur akan berisi 22

:::warning[peringatan]
Jika variable tidak diisi, maka variable itu akan berisi undefined
:::