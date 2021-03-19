# ViewModel

## Fragment 
Fragment merupakan salah satu komponen pada Android Studio dengan fungsi yang hampir sama seperti activity tetapi memiliki “lifecycle” yang berbeda. Fragment merupakan bagian dari sebuah activity yang mana sebuah fragment tidak akan ada bila tidak ada sebuah activity karena fragment membutuhkan akses dari activity untuk dapat dijalankan.

- [x] Sebuah Fragment merupakan kombinasi sebuah layout XML dan kelas java yang mirip dengan sebuah Activity.

- [x] Dengan menggunakan support library, fragment dapat mendukung hampir semua versi Android.

- [x] Fragment dapat dipakai berulang kali didalam activity.

- [x] Fragment merupakan komponen utuh yang memiliki view, event, dan logic (meskipun tetap membutuhkan sebuah fragment agar dapat bekerja).

## ViewPager
Viewpager adalah komponen android yang sering dipakai untuk menampilkan data dalamformat full screen dan bisa berpindah antar data dengan menggeser ke kiri atau kekanan.
ViewPager akan bertugas menampilkan fragment, lalu TabLayout akan menjadi navigasinya. Setiap page bisa berisi layout yang berbeda-beda, karena akan ditangani oleh Fragment dan kita bisa mengisinya dengan apapun yang diinginkan. Contoh penerapan viewpager ada pada aplikasi whatsapp.

## ViewModel
ViewModel adalah sebuah kelas yang dirancang untuk menyimpan dan mengelola data yang biasanya berhubungan dengan UI. Sehingga data tersebut dapat digunakan kembali saat terjadi perubahan konfigurasi.
ViewModel berfungsi menyimpan dan mengembalikan data yang terikat dengan suatu activity maupun fragment sehingga aplikasi kita dapat menggunakan data yang sebelumnya sudah dimiliki.
Tanggung jawab ViewModel hanyalah mengelola data untuk UI. Itu tidak boleh mengakses hierarki tampilan Anda atau menahan referensi kembali ke Aktivitas atau Fragmen.

## Intro Slider dan splash screen
Intro Slider ialah tampilan beberapa slide yang bisa di geser oleh user sebelum masuk ke menu utama pada sebuah aplikasi. 
Splash screen adalah istilah yang diberikan pada layar pembuka setiap kali kita menjalankan sebuah aplikasi Android. Fungsi dari splash screen tersebut bermacam-macam, ada yang digunakan untuk load data, untuk menjalankan file konfigurasi, atau untuk proses suatu algoritma tertentu. Namun, ada juga splash screen yang tidak ada fungsinya sama sekali, khusus digunakan untuk tampilan awal saja. 
