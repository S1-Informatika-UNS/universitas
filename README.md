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