1. Dari milestone 1 ini saya mempelajari kalau sebuah web server sederhana bisa dibuat dari hanya menjalankan server di localhost dan menunggu koneksi dari browswer. Ketika browser mengakses alamat tersebut, server akan menerima koneksi lalu membaca request yang dikirimkan. Dari proses ini saya memahami bahwa browser dan server berkomunikasi melalui mekanisme request dan response. 

Pada tahap ini servernya masih belum mengirim response, sehingga browser masih menampilkan error saat halaman diakses. Walaupun begitu, request dari browser udah bisa terlihat di terminal, jadi bisa bener-bener memastikan kalau server udah menerima koneksi dengan benar. Menurut saya, milestone ini penting karena menjadi fondasi untuk memahami alur kerja web server sebelum masuk ke tahap mengirim response dan menampilkan HTML.

2. [Commit 2 screenshot](images/commit2.png)
Dari milestone 2 ini saya mempelajari kalau server tidak cukup hanya menerima request dari browser, tetapi juga harus mengirim response yang benar supaya halaman bisa ditampilkan. Pada tahap ini, program mulai membaca isi file HTML lalu mengirimkannya kembali ke browser sebagai response HTTP. Proses ini membuat saya memahami bahwa halaman yang muncul di browser itu berasal dari response yang dikirim oleh server. 

Saya juga jadi melihat kalau bagian seperti status line dan Content-Length punya peran penting supaya browser bisa membaca isi balasan dengan benar. Setelah perubahan ini di-run, browser sudah tidak hanya menampilkan error lagi dan menampilkan halaman HTML sederhana. Milestone ini penting karena membuat alur komunikasi antara server dan browser jadi lebih jelas sebelum masuk ke tahap validasi request dan penanganan halaman yang berbeda.

3. 