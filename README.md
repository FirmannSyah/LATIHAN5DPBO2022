# LATIHAN5DPBO2022

## Saya Muhamad Firmansyah 2010021 mengerjakan Latihan 5 DPBO dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin

Sebuah repository untuk mengunggah kodingan dari latihan dpbo 2022

a. Mengganti font dan ukuran teks
   Tahap ini dapat dilakukan dengan cara melakukan klik kanan pada komponen yang ingin diubah. Pilih menu `Properties`. Lalu ubah jenis font dan ukuran teks.
   Font yang digunakan adalah `Poppins` dengan default size `12`. Namun, pada title diberikan font size `36`\
b. Mengubah nama variabel setiap komponen
   Tahap ini dapat dilakukan dengan cara melakukan klik kanan pada komponen yang ingin diubah. Pilih menu `Change Variable Name`. Lalu ubah nama variabel sesuai dengan
   fungsi/jenis komponennya. \
c. Menambahkan validasi ketika inputan tidak lengkap, seperti memunculkan pesan error menggunakan class JOptionPane
   Tahap ini dapat dilakukan dengan cara menambahkan satu method baru, yaitu `checkingData()` dan dengan memanfaatkan fungsi `equals("")`. Method akan dipanggil disetiap
   input maupun update. Jika method return 1, maka `JOptionPane` akan mengeluarkan pesan "Harap lengkapi data!". \
d. Menghapus data pada label inputan ketika sudah selesai add, update, delete, maupun ketika menekan tombol cancel
   Tahap ini dapat dilakukan dengan cara mereset isi semua variabel inputan dengan menggunakan `setText("")`. Setelah action pada suatu button dilakukan maka kode
   berikut akan dijalankan.
   ```
   txtNIM.setText("");
   txtName.setText("");
   txtScore.setText("");
   txtClass.setText("");
   ```
e. Mengupdate tabel setiap kali ada perubahan pada data hasil add, update dan delete
   Tahap ini dapat dilakukan dengan cara mengupdate tabel dengan menggunakan kode `tableRecord.setModel(setTable());` setelah modifikasi dilakukan.

