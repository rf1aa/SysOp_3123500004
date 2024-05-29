<div align="center">
  <h1 style="text-align: center;font-weight: bold">Praktikum 9<br>Praktek Sistem Operasi</h1>
  <h4 style="text-align: center;">Dosen Pengampu : Dr. Ferry Astika Saputra, S.T., M.Sc.</h4>
</div>
<br />
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/id/4/44/Logo_PENS.png" alt="Logo PENS">
  <h3 style="text-align: center;">Disusun Oleh : </h3>
  <p style="text-align: center;">
    <strong>Fauzan Abderrasheed (3123500020) </strong><br>
    <strong>Muhammad Rafi Dhiyaulhaq (3123500004) </strong><br>
    <strong>Arva Zaki Fanadzan (3123500014)</strong>
  </p>
<h3 style="text-align: center;line-height: 1.5">Politeknik Elektronika Negeri Surabaya<br>Departemen Teknik Informatika Dan Komputer<br>Program Studi Teknik Informatika<br>2023/2024</h3>
  <hr><hr>
</div>

## Producer Consumer Semaphore

![App Screenshot](img/semaphore.png)

Analisa: 

Program diatas contoh implementasi dari Producer Consumer Semaphore problem dalam bahasa C. Dalam kasus ini, menu yang terdapat dalam program terdapat 3 menu, yaitu pertama Producer, kedua Consumer, dan ketiga Exit. Menu pertama Producer adalah untuk membuat data dengan maximal data sebanyak 3, jika user memilih opsi 1 berturut-turut sampai lebih dari 3 kali maka akan mencetak pesan "Buffer is full!!" yang mengartikan bahwa storage buffer sudah penuh. Begitu juga sebaliknya jika user memilih menu kedua secara berturut-turu sampai lebih dari 3 kali, maka akan mencetak pesan "Buffer is empty!!" yang menandakan bahwa buffer sudah kosong/tidak ada isinya. Menu ketiga untuk keluar dari program.

## Producer Consumer Wake-Sleep thread

![App Screenshot](img/wake-sleep.png)

Analisa : 

Program diatas contoh implementasi dari Producer Consumer Semaphore problem menggunakan thread dalam bahasa C++. Dalam kasus ini, program menggunakan thread untuk menjalankan produsen dan konsumen secara bersamaan. Dengan menggunakan mekanisme seperti kunci gembok (mutex) dan lampu lalu lintas (variabel kondisi), program memastikan bahwa hanya satu proses yang dapat mengakses sumber daya pada satu waktu. Saat produsen menghasilkan sesuatu, ia memberitahu konsumen dengan cara mengirim sinyal bahwa ada barang baru yang tersedia. Begitu juga ketika konsumen mengonsumsi barang, ia memberi tahu produsen dengan cara mengirim sinyal bahwa ia sudah mengambil barang tersebut. Dengan demikian, program memastikan bahwa proses produksi dan konsumsi berjalan dengan aman dan terkoordinasi.

### Referensi

- [Producer Consumer Problem](https://www.geeksforgeeks.org/producer-consumer-problem-in-c/)