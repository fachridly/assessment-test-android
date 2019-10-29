# assessment-test-android
Tugas lamaran pekerjaan untuk posisi android developer

Jawaban soal:
1.  Relative layout
2.  File manifest
3.  A.OnCreate() - A.OnStart() - A.OnResume() - A.OnPause() - B.OnCreate() - B.OnStart() - B.OnResume()
4.  Default
5.  Instance variable atau global variable merupakan variable yang dapat dibuat pada baris paling atas di dalam suatu class dan dapat   diakses oleh konstruktor, prosedur, maupun fungsi-fungsi yang ada di dalam class tersebut. Sedangkan local variable merupakan variable yang dibuat pada konstruktor, prosedur, fungsi, percabangan, atau perulangan yang ada dalam suatu class, yang mana hanya dapat diakses di tempat variable tersebut dibuat, misal jika kita membuatnya di dalam suatu perulangan maka variable tersebut hanya dapat digunakan di dalam perulangan tersebut.
6.  git clone urlrepositoridigithub
7.  git config --global user.email alamatemailyangingindigunakansecaraglobal
8.  Akan memanggil method onPause() yang di mana di dalamnya akan mengecek nilai return dari method isFinishing(). Jika bernilai true, maka akan menampilkan toast pada aplikasi bertuliskan Finishing , sedangkan jika bernilai false maka akan menampilkan toast pada aplikasi yang bertuliskan In Background dengan durasi yang lebih lama dibanding jika bernilai true.
9.  permission dideklarasikan bukan di dalam application tetapi diluar sebelum deklarasi application
10. Akan menampilkan pesan log bertipe debug di dalam logcat dengan pesan habis dibagi tiga dengan tag BINAR. Berarti percabangan pertama saja yang akan terpanggil karena syaratnya telah terpenuhi dan secara otomatis opsi lainnya tidak akan terpanggil walaupun syaratnya sesuai.
11. Aplikasinya bernama Catatan Toko Binar dengan beberapa user dengan username dan password serta hak aksesnya:
  a. username: admin, pass: qwerty1 -> hak akses: dapat mencatat barang-barang yang masuk (dapat menjalankan fungsi CRUD)
  b. username: employee2, pass: qwerty2 -> hak akses: hanya dapat melihat list barang-barang yang masuk (hanya dapat menjalankan fungsi read)
  c. username: employee3, pass: qwerty3 -> hak akses: sama seperti user employee2
  d. username: employee4, pass: qwerty4 -> hak akses: sama seperti user employee2
  e. username: employee5, pass: qwerty5 -> hak akses: sama seperti user employee2
