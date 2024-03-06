<div align="center">
  <h1 style="text-align: center;font-weight: bold">Praktikum 1<br>Sistem Operasi</h1>
  <h4 style="text-align: center;">Dosen Pengampu : Dr. Ferry Astika Saputra, S.T., M.Sc.</h4>
</div>
<br />
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/id/4/44/Logo_PENS.png" alt="Logo PENS">
  <h3 style="text-align: center;">Disusun Oleh : </h3>
  <p style="text-align: center;">
    <strong>Muhammad Rafi Dhiyaulhaq (312350004) </strong><br>
    <strong>Arva Zaki Fanadzan (3123500014) </strong><br>
    <strong>Fauzan Abderrashed (3123500020)</strong>
  </p>
<h3 style="text-align: center;line-height: 1.5">Politeknik Elektronika Negeri Surabaya<br>Departemen Teknik Informatika Dan Komputer<br>Program Studi Teknik Informatika<br>2023/2024</h3>
  <hr><hr>
</div>

## Daftar Isi
1. [Pendahuluan](#Pendahuluan)
2. [Soal](#soal)

##Pendahuluan
Apa itu Sistem Operasi?<br>
<strong>Sistem Operasi</strong> adalah perangkat lunak pada lapisan pertama yang ditempatkan pada memori komputer pada saat komputer dinyalakan (<i>booting</i>). Sedangkan <i>software</i> lainnya dijalankan setelah sistem operasi berjalan, dan sistem operasi akan melakukan layanan inti untuk software tersebut.

## Soal
#### Sebutkan dan jelaskan proses booting !
1 . <strong>Power ON</strong>
![Screenshot](aset/img/1.jpg)
Saat tombol power atau tombol reset dihidupkan, sumber daya listrik akan mengalir ke komputer.
Kemudian, perangkat keras akan menerima daya untuk dinyalakan.

2 . <strong>POST (Power On Selft Test)</strong>
![Screenshot](aset/img/2.jpg)
Setelah dinyalakan, komputer akan melakukan Power-On Self-Test atau POST, yang merupakan serangkaian tes perangkat keras untuk memastikan bahwa semuanya berfungsi dengan baik. 
POST akan memeriksa RAM, prosesor, kartu grafis, dan perangkat keras lainnya. 

3 . <strong>Inisialisasi perangkat keras</strong>
![Screenshot](aset/img/3.jpg)
Setelah POST selesai, komputer akan menginisialisasi perangkat keras seperti hard drive, keyboard, mouse, dan perangkat lainnya. 
Proses ini melibatkan tahap mengenali perangkat keras, memuat driver yang diperlukan, dan menyiapkan perangkat untuk digunakan.

4 . <strong>Membaca sektor boot</strong>
![Screenshot](aset/img/4.jpg)
Selanjutnya, komputer akan mencari sektor boot di hard drive atau perangkat penyimpanan lainnya. 
Sektor boot adalah area khusus yang berisi instruksi awal untuk memuat sistem operasi.

5 . <strong>Memuat Sistem Operasi</strong>
Setelah sektor boot ditemukan, komputer akan memuat sistem operasi ke dalam memori utama (RAM). 
Kemudian, sistem operasi akan mengambil alih kendali dan mulai menjalankan program-program yang diperlukan untuk mengoperasikan komputer.

#### Bagaimana cara install Oracle Virtual Box dan Debian dalam Virtual Box ?

## Instalasi Oracle Virtual Box
1. Masuk ke laman [Oracle Virtual box](https://www.virtualbox.org/wiki/Downloads), lalu unduh sesuai sistem operasi yang anda gunakan. Disini saya sudah menambahkan file Oracle Virtualbox beserta file Debian yang nanti akan digunakan
![Screenshot](img/Virtual/1.png)

3. Buka setup Oracle dan klik Next.
![Screenshot](img/Virtual/2.png)

4. Klik Install.
![Screenshot](img/Virtual/3.png)

5. Oracle sedang dalam proses pengunduhan.
![Screenshot](img/Virtual/4.png)

6. Oracle Virtual Box telah di install, klik finish.
![Screenshot](img/Virtual/5.png)

6.Tampilan awal akan terlihat seperti ini
![Screenshot](img/Virtual/6.png)

## Instalasi Linux Debian dalam Oracle Virtual Box
1. Buka Oracle Virtual Box, lalu klik opsi "New".
![Screenshot](img/Virtual/6.png)

2. Isi nama, pilih letak penyimpanan Virtual Box, masukkan file ISO debian yang telah diunduh, klik "Skip unattended Installation, dan klik Next.
![Screenshot](img/Debian/2.png)

3. Tentukan RAM dan jumlah CPU yang diinginkan, lalu klik Next.
![Screenshot](img/Debian/3.png)

4. Tentukan ukuran storage didalam Virtual Machine,  lalu klik Next.
![Screenshot](img/Debian/4.png)

5. Dalam tampilan ini, anda dapat melihat ulang pilihan yang anda telah pilih sebelumnya, jika sudah sesuai keinginan, pilih Finish.
![Screenshot](img/Debian/5.png)

Ini adalah tampilan Linux Debian pada Oracle
![Screenshot](img/Debian/6.png)

## Mengkonfigurasi Debian dalam Oracle Virtual Box
1. Klik "Start" untuk membuka Virtual Machine.
![Screenshot](img/Debian/6.png)

2. Pilih Graphical Install untuk memulai konfigurasi Debian.
![Screenshot](img/Debian/7.png)

3. Pilih Bahasa, lalu klik continue.
![Screenshot](img/Debian/8.png)

4. Pilih lokasi, lalu klik continue.
![Screenshot](img/Debian/9.png)

5. Pilih konfigurasi bahasa Keyboard, lalu klik continue.
![Screenshot](img/Debian/11.png)

6. Isi Hostname, lalu klik continue.
![Screenshot](img/Debian/13.png)

7. Untuk nama domain tidak perlu diisi, klik continue.
![Screenshot](img/Debian/14.png)

8. Isi root password, lalu klik continue.
![Screenshot](img/Debian/15.png)

9. Isi nama, lalu klik continue.
![Screenshot](img/Debian/17.png)

10. Isi username, lalu klik continue.
![Screenshot](img/Debian/18.png)

11. Pilih lokasi jam, lalu klik continue.
![Screenshot](img/Debian/21.png)

12. Untuk partition disk, pilih manual, lalu klik continue.
![Screenshot](img/Debian/23.png)

13. Pilih opsi seperti pada gambar dibawah, lalu klik continue.
![Screenshot](img/Debian/24.png)

14. Pilih "Yes" untuk membuat partition disk baru, lalu klik continue.
![Screenshot](img/Debian/25.png)

15. Pilih pri/log untuk membuat bagian partition disk, lalu klik continue.
![Screenshot](img/Debian/26.png)

16. Pilih "create new partition disk" untuk membuat partition disk, lalu klik continue.
![Screenshot](img/Debian/27.png)

17. Tentukan jumlah penyimpanan partition disk pertama, lalu klik continue.
![Screenshot](img/Debian/29.png)

18. Pilih "primary" agar menjadikan penyimpanan utama, lalu klik continue.
![Screenshot](img/Debian/30.png)

19. Pilih "beginning", lalu klik continue.
![Screenshot](img/Debian/31.png)

20. pilih opsi "done setting up the partition" klik continue.
![Screenshot](img/Debian/33.png)

21. Setelah membuat partition disk pertama, silahkan membuat partition disk ke dua, tentukan isi penyimpanan yang ukurannya lebih kecil dibandingkan partition disk pertama, lalu klik continue.
![Screenshot](img/Debian/34.png)
![Screenshot](img/Debian/35.png)
![Screenshot](img/Debian/37.png)


23. Untuk partition disk kedua, pilih opsi primary dan pada mount point pilih Enter manually dan ketik "/storage", lalu klik continue.
![Screenshot](img/Debian/41.png)
![Screenshot](img/Debian/42.png)
![Screenshot](img/Debian/43.png)

25. Setelah membuat partition disk kedua, silahkan membuat partition disk ke tiga, tentukan isi penyimpanan yang ukurannya lebih kecil dibandingkan partition disk kedua, lalu klik continue.
![Screenshot](img/Debian/47.png)

26. Untuk partition disk kedua, pilih opsi logical, lalu jadikan "swap area" pada bagian "use as:", lalu klik continue.
![Screenshot](img/Debian/52.png)

27. Cek ulang seperti gambar dibawah, jika sudah sesuai, klik continue.
![Screenshot](img/Debian/54.png)

28. Pilih opsi "No", lalu klik continue.
![Screenshot](img/Debian/55.png)


29. Pilih opsi "No", lalu klik continue.
![Screenshot](img/Debian/59.png)

30. Pilih lokasi terdekat untuk mengunduh package manager, lalu klik continue.
![Screenshot](img/Debian/60.png)

31. Pilih archive mirror, lalu klik continue.
![Screenshot](img/Debian/61.png)

32. Pada bagian ini tidak perlu diisi, klik continue
![Screenshot](img/Debian/62.png)

33. Pilih opsi "Yes", lalu klik continue.
![Screenshot](img/Debian/63.png)

35. Tidak perlu mengubah apa-apa, tekan continue.
![Screenshot](img/Debian/64.png)

36. Pilih opsi yes, lalu klik Continue
![Screenshot](img/Debian/66.png)

37. Pilih /dev/sda, lalu klik continue.
![Screenshot](img/Debian/67.png)

39. Instalasi dan konfigurasi Debian telah selesai, klik continue dan Virtual machine akan me-reboot. 
![Screenshot](img/Debian/68.png)

40. Tampilan Linux Debian setelah reboot.
![Screenshot](img/Debian/69.png)
![Screenshot](img/Debian/74.png)
