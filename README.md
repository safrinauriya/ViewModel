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

![ezgif com-video-to-gif](https://user-images.githubusercontent.com/60589670/111824747-2e5d8280-8919-11eb-9344-f06621ef54e8.gif)

## Intro Sliders
![Screenshot_20210320-081810_ViewModel](https://user-images.githubusercontent.com/60589670/111856327-7f429a80-895c-11eb-8455-046cd8fa3f70.jpg)
![Screenshot_20210320-081835_ViewModel](https://user-images.githubusercontent.com/60589670/111856325-7c47aa00-895c-11eb-8724-c187521b08fa.jpg)
![Screenshot_20210320-081818_ViewModel](https://user-images.githubusercontent.com/60589670/111856328-8073c780-895c-11eb-8f64-58a833c087a7.jpg)
![Screenshot_20210320-081826_ViewModel](https://user-images.githubusercontent.com/60589670/111856329-81a4f480-895c-11eb-936f-8c9a5a422b38.jpg)

## Form Pengisian Data (Fragment1)
![Screenshot_20210320-081941_ViewModel](https://user-images.githubusercontent.com/60589670/111856347-a8fbc180-895c-11eb-881c-e737e1c11222.jpg)

## Form Tampilan Data (Fragment2)
![Screenshot_20210320-081948_ViewModel](https://user-images.githubusercontent.com/60589670/111856345-a6996780-895c-11eb-9c7e-17325fc87921.jpg)
