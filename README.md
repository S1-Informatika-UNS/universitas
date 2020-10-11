# Praktikum 3-4 PBO : Inheritance dan Enkapsulasi

## S1 Informatika UNS

> Silakan posting di grup kelas / Spada apabila anda masih belum memahami instruksi berikut. 

1. Clone repository ini dengan perintah ```git clone alamat_url_repository``` atau gunakan Git GUI client.

2. Ini adalah project aplikasi Java yang dibuat menggunakan [gradle build tool](https://gradle.org/). Terdapat banyak file yang digenerate, jangan hapus file-file tersebut. Yang perlu anda lakukan adalah membuat class di folder **/src/main/java/com/univ**

![inheritance](https://github.com/S1-Informatika-UNS/universitas/blob/main/img/inheritance.jpg "inheritance")

3. Perhatikan gambar class diagram di atas, terdapat sebuah kasus mengenai gaji pegawai pada suatu universitas. Setiap sub-class terbawah memungkinkan memiliki total gaji yang berbeda-beda.  Adapun deskripsi detail mengenai total gaji yang akan dijelaskan pada berikut ini:

* Total gaji dosen PNS = Gaji tetap + Remunerasi + Tunjangan
* Total gaji dosen Non-PNS = Gaji tetap + Remunerasi
* Total gaji dosen kontrak = Gaji sks + Remunerasi
* Total gaji staff PNS = Gaji tetap + Remunerasi + Tunjangan
* Total gaji staff Non-PNS = Gaji tetap + Tunjangan
* Total gaji staff kontrak = Gaji tetap + Remunerasi

4. Petunjuk :
Setiap kotak yang ada pada class diagram mewakili sebuah class. Anda harus membuat class Pegawai, class Dosen, class DosenPns, class DosenNonPns, class DosenKontrak, class Staff, class StaffPns, class StaffNonPns, classStaffKontrak.
Tanda panah menunjukkan sebuah class merupakan subclass (turunan) dari class induk, contoh : Dosen adalah subclass dari Pegawai, DosenPns adalah subclass dari Dosen, dll.
Pada setiap class sudah terdapat atribut dan method yang harus dibuat, contoh
Class Pegawai memiliki atribut private gajiTetap dengan tipe data int.
Class Pegawai memiliki method public getGajiTetap() dengan return value int
Class Pegawai memiliki method public setGajiTetap(int) dengan parameter sebuah variabel int
Keterangan : tanda (-) di depan nama atribut / method artinya atribut / method tersebut menggunakan access modifier private
tanda (+) di depan nama atribut / method artinya atribut / method tersebut menggunakan access modifier public

5. Tugas kalian adalah membuat program yang mengimplementasikan struktur inheritance seperti class diagram universitas di atas, adapun keterangan nominal gaji setiap pegawai adalah seperti tabel di bawah ini.

| No   |   Jenis Gaji   |   Nominal   |
| ------------- |:-------------:| -----:|
| 1   | gajiTetap   |   5857500   |
| 2   | tunjangan Dosen   |   2613000   |
| 3   | tunjangan Staff   |   1750000   |
| 4   | remunerasi DosenPns   |   1425000   |
| 5   | remunerasi DosenNonPns   |   1050000   |
| 6   | remunerasi DosenKontrak   |   1500000   |
| 7   | gajiSks DosenKontrak   |   6750000   |
| 8   | remunerasi StaffPns   |   1995000   |
| 9   | remunerasi StaffKontrak   |   1300000   |