# Praktikum8
`Nama  : Fadilah adeliani putri`</br>
`Kelas : TI.22.B2`</br>
`NIM   : 312210055`</br>

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

- selanjutnya buatlah Method `ubah()` ini berfungsi sebagai menu mengubah data yang telah diinput, Inputan tersebut didalamnya terdapat atribut nama, Sedangkan untuk penginputan sebuah nim, tugas, uts, dan uas dapat kita ubah sesuai kebutuhan.
- selanjutnya buatlah Method `hapus()` ini berfungsi untuk penghapusan sebuah data pada program yang sebelumnya telah diinput. Dan inputan dari kodingan ini berdasarkan "nama" yang sebelumnya telah diinput.
seperti gambar dibawah ini 
<img width="960" alt="ss3" src="https://user-images.githubusercontent.com/115479946/206894550-55e810cd-8cfa-4b8b-9a19-490c96d28022.png">

- Untuk menjalankan program sama seperti tugas sebelumnya,kita bisa input melalui masing-masing methods, seperti pada sebuah while loop yang didalamnya Terdapat conditional seperti gambar dibawah ini.
- yang terakhir jika data sudah selesai diinput, Pilih menu ke (Keluar) yaitu `"k"`, Maka program secara otomatis akan berhenti.
seperti gambar dibawah ini 

<img width="958" alt="ss4" src="https://user-images.githubusercontent.com/115479946/206894554-e7fb955d-dda9-4dd2-ae75-f148fa187dd4.png">

<img width="958" alt="ss5" src="https://user-images.githubusercontent.com/115479946/206894559-2ce71e31-5d7f-4f24-8604-8618b5f57dc1.png">

<img width="954" alt="ss6" src="https://user-images.githubusercontent.com/115479946/206894564-8c40e419-092a-42cc-9ba9-73a02283cef9.png">

<img width="958" alt="ss7" src="https://user-images.githubusercontent.com/115479946/206894568-d243c2bd-e587-41f3-8043-adcd970665ed.png">

### Hasil Outputnya 
- Apabila program dijalankan maka akan menghasilkan output sebagai berikut :
- Menambahkan Data dengan input `t` 

<img width="959" alt="tambah" src="https://user-images.githubusercontent.com/115479946/206895223-85e717fb-6b3f-4799-a42e-6519417b2049.png">

- Menampilkan data dengan input `l`
<img width="955" alt="lihat" src="https://user-images.githubusercontent.com/115479946/206895290-0b950624-36b1-4b16-8f11-7d5368b95450.png">

- Mengubah data dengan input `u`
<img width="959" alt="ubah" src="https://user-images.githubusercontent.com/115479946/206895299-910545d4-a41f-486c-a2af-995d4456cf42.png">

- Menghapus data dengan input `h` dan keluar dengan input `k`
<img width="957" alt="hapus" src="https://user-images.githubusercontent.com/115479946/206895295-94a98848-0c85-4f14-b534-c99f1a449de2.png">
