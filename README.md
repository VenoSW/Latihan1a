# Latihan VCS
VCS merupakan sebuah sistem yang merekam perubahan-perubahan dari sebuah berkas atau
sekumpulan berkasdari waktu ke waktu sehingga anda dapat melihat kembali setiap perubahannya.
Salah satu DVCS (Dsitributed Version Control System) yang sangat populer saat ini adalah GIT.

Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek
perangkat lunak yang diciptakan oleh Linus Torvalds.

# Cara membuat repositori di GIT
1. Buka aplikasi “Git Bash”
2. Masuk ke penyimpanan file yang akan dibuat misal akan dibuat di direktori C dengan command "cd /c”
3. Buat file terlebih dahulu dengan command "mkdir Latihan1"
4. Lalu masuk ke dalam file yg telah dibuat dengan command "cd /c/Latihan1"
5. Lalu command “git init”. Git init untuk meng-set folder yang digunakan tersebut sebagai repo local git. Bisa di bilang ini instalasi git pertama kali.
6. Lalu buat file README.md dengan command “echo “# Latihan1” > README.md
7. Setelah itu isi file README.md dengan tugas yang sudah diberikan dengan command “nano README.md”
8. Lalu command "git init"
9. Kemudian command "git add README.md". Git add adalah perubahan yang diajukan atau file tambahan akan ditambahkan ke index dengan menggunakan perintah add.
10. Langkah selanjutnya adalah mengkomit file dengan command “git commit -m “isi commit”. Git commit untuk menambahk keterangan/status perubahaan saat upload ke repo online.
11. Lalu meremot repositori yang sudah dibuat di github dengan command “git remote add origin https://github.com/VenoSW/Latihan1a.git (bisa diganti link repositori anda sendiri”.
12.	Lalu upload file README.md ke repositori online dengan command “git push -u origin master”
13.	Kemudian command “git pull origin master”. Git pull untuk mengambil commit terbaru lalu otomatis menggaubungkan (merge) dengan branch yang aktif.
14.	Terakhir mengecek file yang README.md yang sudah diupload dengan command “ll”

Copyright VenoSW 2019
