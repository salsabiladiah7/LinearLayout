# Activity
>
 Activity adalah sebuah komponen aplikasi yang menyediakan layar yang digunakan user untuk berinteraksi guna melakukan sesuatu, misalnya memilih data, mengambil data, mengirim atau menampilkan data. Satu aplikasi bisa memiliki lebih dari satu Activity, dan setiap Activity memiliki siklus hidup (*lifecycle*). . Ada dua metode yang pasti dimiliki oleh satu activity yaitu :
1. **onCreate** adalah kondisi awal saat Activity baru diciptakan, biasanya dipanggil dengan perintah setContentCiew(int) untuk resource yang didefinisikan di layout UI, dengan perintah findViewById(int) untuk memanggil widget yang dibutuhkan UI untuk berinteraksi dengan aplikasi.
2. **onPause** Untuk menyatakan ketika user meninggalkan suatu activity. Untuk penggunaan dengan Context.StartActivity(), semua kelas activity harus sesuai dengan yang dideklarasikan dalam suatu paket di AndroidManifest.xml.  Sistem memanggil onPause() saat ada Activity lain yang terbuka

# Layout
> Layout merupakan suatu tampilan tata letak di Android untuk mengatur penempatan teks, gambar, ataupun komponen lainnya sehingga tampilan pada aplikasi yang dibuat terlihat rapih dan nyaman untuk dilihat oleh pengguna.
- **Linear Layout** 
  Linear Layout adalah susunan tata letak yang paling simple dapat digunakan paradeveloper android. Karena layout ini hanya memberikan susunan tata letak komponen secara garis lurus. Bisa secara horizontal atau vertical.
- **Relative Layout**
  Relative Layout adalah desain tampilan pada aplikasi dengan tata letak objek atau komponen secara bebas tanpa aturan sesuai orientasi (horizontal atau vertical). Untuk relative layout bisa diatur mengikuti komponen lainnya, karena komponen satu dan lainnya saling berkaitan.
- **Constraint Layout**
  Sebenarnya Constraint Layout mirip dengan Relative Layout, karena letak komponennya bergantung pada komponen lain dalam satu Layout. Akan tetapi, Constraint Layout jauh lebih fleksibel dan lebih mudah digunakan di Layout Editor. Pada Constraint Layout, setiap View memiliki tali (Constraint) yang menarik tiap sisinya, yang mana tali tersebut bisa kita atur Elastisitas, Margin, dsb. 
  
> **Perbedaan Linear Layout, Relative Layout, Constraint Layout**
Letak perbedaan di antara ketiga layout tersebut adalah pada susunan atau tata letak komponennya. Setiap layout tersebut memiliki sistem sendiri untuk menyesuaikan tata letak  komponennya. Linear layout bisa mengikuti ukuran layar handphone yang berbeda-beda tanpa merubah susuan objek. Relative layout hanya akan terlihat sesuai dengan apa yang telah ditetapkan sebelumnya, jika ukuran layar berubah bisa saja objek ada yang terpotong atau bahkan tidak terlihat. Sedangkan constraint layout itu lebih flexible dan mudah dalam pembuatan dan penyesuaiannya.
  
# Contoh LinearLayout
![Screenshot_2021-02-09-22-17-51-30_2af3ab07f3de21ef00afb52b1fbfbc85](https://user-images.githubusercontent.com/60590053/107386375-60174880-6b26-11eb-85a7-f57507d38d04.jpg)

#Terima Kasih
