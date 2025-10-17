# Tugas PBO Pertemuan 9
Langkah-langkah Instalasi iReport dan Integrasi dengan NetBeans/JDK 20+ 
1. 	Buka Chrome, mencari iReport plugin for netbeans dan kemudian klik bagian download iReport-5.6.0-plugin.zip, nanti saat tampilan/halaman nya dialihkan. Maka zip akan terunduh otomatis.
2. 	Setelah install iReport plugin for netbeans, kita lanjut menginstall org-jdesktoplayout-RELEASE65, supaya nanti kita dapat menginstall iReport plugin di netbeans, tapi jika sudah terinstall di plugin netbeans maka tidak perlu menginstall lagi dibrowser.
3.	Setelah kita selesai menginstall iReport dan jdesktop layout, kita buka netbeans, klik tools dan klik plugin, kemudian pilih bagian download, sebelum buka netbeans jangan lupa zipnya di ekstrak terlebih dahulu supaya dapat di pilih file iReportnya. Pada  bagian download klik add plugin dan pilih file pada zip tersebut yaitu ada 4 seperti di gambar dan kemudian pilih file jdesktop layout yang sudah kita install tadi. Jadi ada 5 file yang akan kita install di plugin netbeans. 
<img width="917" height="516" alt="image" src="https://github.com/user-attachments/assets/058b31c8-b2dc-4f35-b3be-c4118ef64e71" />
<img width="917" height="516" alt="image" src="https://github.com/user-attachments/assets/64d11002-2b7b-48b6-a284-992bcd84d8ec" />
<img width="919" height="1049" alt="image" src="https://github.com/user-attachments/assets/a63fecc1-a7da-4365-8f74-5db3525d21c6" />
<img width="917" height="516" alt="image" src="https://github.com/user-attachments/assets/aea1509f-054b-443f-aedb-856b18147038" />
4. Kemudian tampilan akan berubah seperti gambar dibawah, tapi berhubung jdesktop layaout di netbeans saya sudah terinstal maka yang muncul hanya 4 dan kemudian klik install.
<img width="917" height="516" alt="image" src="https://github.com/user-attachments/assets/531850fa-a8a7-4226-90cd-c2d67e59f0bf" />
5.	Setelah itu kita tinggal klik next, dan di page selanjutnya klik i accept dan klik install.
<img width="921" height="519" alt="image" src="https://github.com/user-attachments/assets/c1352c0c-5162-4e89-81c6-72627c0dcd71" />
6.	Kita tunggu sampai prosesnya selesai nanti akan muncul seperti gambar dibawah ini dan kemudian kita klik continue. 
<img width="917" height="516" alt="image" src="https://github.com/user-attachments/assets/1f650117-b078-46e6-8237-063b5be78fb8" />
7.	Kemudian muncul pilihan untuk restart netbeans sekarang atau nanti, disini saya pilih yang sekarang dan kemudian klik finish. Maka netbeans otomatis akan restart.
<img width="917" height="516" alt="image" src="https://github.com/user-attachments/assets/9b2e1e10-3382-48c1-b108-9dfe8ff97510" />
8.	Setelah restart tampilan awal netbeansnya berubah menjadi seperti ini.
<img width="917" height="516" alt="image" src="https://github.com/user-attachments/assets/aaf71bce-178b-44cc-8d92-895e491c01b5" />
9.	Nah,sekarang kita lanjut ke integrasi iReport pada netbeans, pertama kita buka proyek pertemuan sebelumnya yang sudah diganti namanya jadi proyek pertemuan sembilan. Sebelum mengintegrasikan iReport pada netbeans kita perlu menginstall beberapa jar supaya iReport dapat dijalankan. Dalam proyek ini, library belum terisi jar untuk mengintegrasikan iReport.
<img width="619" height="404" alt="image" src="https://github.com/user-attachments/assets/f481e6c3-8d89-4cee-aca2-2939976f4070" />
10.	Sekarang kita perlu menginstall commons-logging-1.2.jar, commons-digester-2.1.jar, AbsoluteLayout.jar, groovy-all-2.4.5.jar, itextpdf-5.5.4.jar, jasperreports-6.21.5.jar dan commons-collections4-4.4.jar.
<img width="556" height="400" alt="image" src="https://github.com/user-attachments/assets/5992a901-d2c4-4ff3-a5a8-bb04e746cc4f" />
11.	Setelah kita menginstall semua jar tersebut, masukkan kedalam library proyek pertemuan kesembilan.
<img width="698" height="535" alt="image" src="https://github.com/user-attachments/assets/40b3e8af-cf9c-41e3-8e03-6e655037ae41" />
12.	Setelah ditambahkan, maka tampilan library akan berubah seperti ini.
<img width="917" height="909" alt="image" src="https://github.com/user-attachments/assets/9766f4ef-6a0d-4977-b009-4cd3031190eb" />
<img width="517" height="387" alt="image" src="https://github.com/user-attachments/assets/82e564a1-1eda-41b3-8333-11dfcc2e5498" />
13.	Kemudian kita buat iReportnya dengan cara klin new file, pilih report kemudian pilih report wizard.
<img width="764" height="430" alt="image" src="https://github.com/user-attachments/assets/e1b2bdd1-351c-444e-8c4f-a77058bcfb13" />
14. Kemudian pilih layout yang diinginkan dan klik next.
<img width="917" height="516" alt="image" src="https://github.com/user-attachments/assets/ffa708fc-ded8-4b2c-b053-d4801fe7fa72" />
15.	Kemudian beri nama pada file, disini saya beri nama Data dan jika sudah klik next.
<img width="917" height="516" alt="image" src="https://github.com/user-attachments/assets/c817926b-8386-4582-b999-4d37ef4b62b5" />
16.	Kemudian klik new untuk connections dengan database dan type data sourcenya kita pilih yang paling atas yaitu database JDBC connection dan isi datanya sesuai koneksi database kita. Jika sudah untuk test apakah sudah benar atau belum bisa klik tes kalo sukses maka sudah terhubung dan klik save untuk menyimpan. Lalu kemudian ketik pada query untuk menampilkan data yang akan di buat laporan dan klik next.
<img width="536" height="388" alt="image" src="https://github.com/user-attachments/assets/fe630d7c-e4cd-42a2-bbf0-f4eef54dd183" />
17.	Kemudian field yang muncul disebelah kiri dipindahkan di sebelah kanan semua dan klik next, kemudian ada muncul 4 grup itu langsung klik next juga dan pada pop up terakhir klik finish.
<img width="846" height="1423" alt="image" src="https://github.com/user-attachments/assets/2a8cabed-a579-4492-a2ed-bcc26793eff4" />
18.	Setelah itu, nanti kita akan ditampilkan layout sesuai yang kita pilih dan kita bisa mendesign sesuai laporan yang kita butuhkan. 
<img width="917" height="858" alt="image" src="https://github.com/user-attachments/assets/3e07d267-971c-441c-98d6-95dc23b1c7b3" />
19.	Kemudian kita klik preview untuk mencompile jrxml dan nanti akan memunculkan file jasper.
<img width="857" height="361" alt="image" src="https://github.com/user-attachments/assets/035afd98-aa0b-4828-aa04-b42322e3212b" />
20.	Setelah file jasper ditambahkan, kita tambahkan import untuk iReport pada source code class form DataPramuka.
<img width="745" height="364" alt="image" src="https://github.com/user-attachments/assets/f7c13316-b417-40d0-a4af-240a54e33f21" />
21.	Pada tombol cetak kita tambahkan source code untuk mencetak laporan berupa pdf.
<img width="917" height="539" alt="image" src="https://github.com/user-attachments/assets/677a4d81-6eef-436b-9922-e2432bb360d1" />
22.	Maka Output dari proyek ini adalah:
<img width="917" height="516" alt="image" src="https://github.com/user-attachments/assets/0aea7906-8fac-414e-ae13-248c12dadc7c" />
<img width="917" height="516" alt="image" src="https://github.com/user-attachments/assets/3ab39bb5-98b6-4608-8e18-2f988563f64a" />











