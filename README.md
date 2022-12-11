# Praktikum8
`Nama  : Fadilah adeliani putri`
`Kelas : TI.22.B2`
`NIM   : 312210055`

## Tugas praktikum 
- Buatlah program sederhana dengan mengaplikasikan penggunaan class. Buatlah class untuk menampilkan daftar nilai mahasiswa, dengan ketentuan;
> - Method *tambah()* untuk menambahkan data
> - Method *tampilkan()* untuk menampilkan data
> - Method *hapus(nama)* untuk menghapus data berdasarkan nama
> - Method *ubah(nama)* untuk mengubah data berdasarkan nama
> - Buatlah diagram class, flowchart dan penjelasan program pada README.md

### Flowchart 
berikut adalah flowchart dari program tersebut 
![flowchart8](https://user-images.githubusercontent.com/115479946/206893790-d47aec6d-7af7-4f2d-9dce-240df3875aee.jpg)

### Penjelasan 
- Langka pertama adalah mendeklarasikan sebuah`class Mahasiswa():` yang didalamnya terdapat atribut  NIM, Nama, nilai tugas, nilai UTS dan nilai UAS. Untuk mendeklarasikan sebuah class didalam OOP kita harus gunakan `def__init__` dan juga `self`.
- Selanjutnya membuat table sebuah menu kita dapat menggunakan fungsi`menutabel():` yang didalamnya terdapat program sebuah menu yang dapat di input.
seperti gambar dibawah ini 

<img width="960" alt="ss1" src="https://user-images.githubusercontent.com/115479946/206894073-57f9289e-9d40-4fea-a1e6-e3fcb97b77c5.png">

- selanjutnya kita perlu menambahkan metode seperti tambah, lihat, hapus dan mengubah data mahasiswa kita dapat menggunakan `append()`agar data yang terakhir ditambahkan ada di urutan list paling akhir.kita bisa masukan data tersebut kedalam metod `tambah()`.
- selanjutnya kita perlu menambahkan  Method `lihat()` Berguna untuk menampilkan seluruh data yang telah ditambahkan. Bila mana data tersebut belum diinput/data tersebut sudah terhapus, Maka akan keluar ouput dengan tulisan "TIDAK ADA DATA". Kita menggunakan for loop untuk menampilkan banyaknya data. Nantinya data akan ditampilkan sebanyak n kali.
seperti gambar dibawah ini 

<img width="960" alt="ss2" src="https://user-images.githubusercontent.com/115479946/206894296-d9aa4311-8078-4f2f-a095-ddac00f6d871.png">
