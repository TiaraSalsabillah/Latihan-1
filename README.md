LATIHAN1

1. Buka situs GIT di google dan ketik (git.scm.com)
2. Kemudian unduh Git sesuai dengan arsitekturkomputer yangkita miliki 64 bit atau 32 bit
3. Setelah di unduh kemudian instal git
4. Klik (Next) hingga proses penginstalan terakhir
5. Sampai di penginstalan terakhir pilih (View Release Notes), kemudian klik tombol finish
6. Setelah Git terinstal di windows, buka CMD
7. Ketik perintah git-version
8. Kemudian membuat global config dengan memasukkan perintah(git config --global user.name "TiaraSalsabillah")
9. Buatlah folder baru dengan nama Latihan1, kemudian klik kanan folder latihan1 dan pilih git bash
10. Ketik perintah (mkdir latihan1)
11. Lalu ketik perintah (cd latihan1)
12. Setelah itu membuat repository local dengan mengetik perintah (git init)
13. Kemudian membuat file repository bernama README.md dengan mengetik perintah (echo "#Latihan1">>README.md)
14. Membuat file baru dalam README.md dengan mengetik perintah (git add README.md)
15. Untuk merubah penyimpanan ke dalam data base ketik perintah (git commit -m "file pertama saya")
16. Setelah itu buka situs http://github.com dan buatlah akun terlebih dahulu
17. Kemudian klik tombol (start a project)
18. Atau dapat klik (icon+) dan klik New Repository
19. Setelah itu isi nama Repository (Latihan1), lalu klik tombol (Create repository)
20. Salin URL untuk menambahkan remote Repository
21. Kemudian buka Git Bash dan ketik perintah (git remote add origin http://github.com/TiaraSalsabillah/Latihan1.git)
22. Selanjutnya untuk mengirim perubahan dari local repository ke server dengan mengetik perintah (git push -u origin mater)
23. Lalu tunggu hingga 100% semua, apabila sudah 100% artinya repository local sudah berhasil di pindahkan ke server
24. Untuk melihat hasilnya pada server, buka halaman website gitbuh.com
25. Kemudian mengclone repository dengan mengetik perintah (git clone https://github.com/TiaraSalsabillah/Latihan1.git)
