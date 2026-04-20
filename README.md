## Commit 1 Reflection

Pada commit pertama ini, saya belajar bagaimana server sederhana mulai menerima dan membaca permintaan dari browser. Ternyata ketika kita membuka alamat di browser, yang dikirim ke server hanyalah teks berisi request seperti “GET” dan beberapa informasi tambahan. Dari sini saya jadi lebih paham bahwa server tidak langsung menampilkan halaman, tetapi harus membaca dulu isi permintaan tersebut sebelum menentukan respon. Saya juga melihat pentingnya memisahkan bagian kode yang menangani koneksi agar program lebih rapi dan mudah dikembangkan ke tahap berikutnya.

## Commit 2 Reflection 

![Commit 2 screen capture](/assets/images/commit2)

Pada commit kedua ini, saya belajar bagaimana server tidak hanya menerima request, tetapi juga mulai mengirimkan response yang bisa ditampilkan di browser dalam bentuk halaman HTML. Saya jadi lebih paham bahwa server harus menyusun response dengan format tertentu, termasuk status dan isi halaman, agar browser bisa memprosesnya dengan benar. Selain itu, saya juga menyadari bahwa file HTML yang dibuat bisa langsung dibaca dan dikirim oleh server, sehingga isi halaman bisa diubah sesuai kebutuhan. Dari sini saya mulai melihat bagaimana komunikasi antara server dan browser bekerja secara lebih nyata, bukan hanya sekadar teori.

## Commit 3 Reflection 

![Commit 3 screen capture](/assets/images/commit3)

Pada commit ketiga ini, saya belajar bagaimana server mulai membedakan request yang masuk dan memberikan response yang berbeda sesuai dengan permintaan tersebut. Tidak semua request lagi langsung diarahkan ke halaman utama, tetapi server mulai melakukan pengecekan sederhana terhadap path yang diminta oleh browser. Jika request sesuai, server mengembalikan halaman utama, sedangkan jika tidak sesuai, server akan mengembalikan halaman 404. Dari sini saya jadi lebih memahami pentingnya validasi request dalam membangun web server, serta bagaimana logika sederhana seperti kondisi if-else dapat digunakan untuk mengontrol alur response. Saya juga melihat bahwa pemisahan antara status dan file yang dikirim membuat kode lebih rapi dan mudah dikembangkan ke tahap selanjutnya.

## Commit 4 Reflection

Pada commit keempat ini, saya belajar bagaimana server yang berjalan secara single-thread bisa mengalami masalah ketika ada request yang lambat. Dengan menambahkan simulasi delay pada endpoint tertentu, saya melihat bahwa saat satu request membutuhkan waktu lama untuk diproses, request lain harus menunggu sampai proses tersebut selesai. Hal ini membuat saya memahami bahwa server sederhana yang dibuat masih memiliki keterbatasan dalam menangani banyak request secara bersamaan. Dari sini saya jadi lebih paham pentingnya concurrency atau pengolahan paralel dalam pengembangan web server, agar performa tetap baik ketika ada banyak pengguna yang mengakses secara bersamaan.

