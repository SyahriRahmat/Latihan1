# Tutorial Penggunaan Git <h1>

# Mengenal Git <h2>
* Git adalah salah satu sistem pengontrol versi (_Version Control
System_) pada proyek perangkat lunak yang diciptakan oleh Linus
Torvalds. 
* Pengontrol versi bertugas mencatat setiap perubahan pada file
proyek yang dikerjakan oleh banyak orang maupun sendiri. 
* Git dikenal juga dengan distributed revision control (_VCS terdistribusi_),
artinya penyimpanan database Git tidak hanya berada dalam satu
tempat saja

# Perintah Dasar Git <h2>
* _**git init**_, perintah untuk membuat repository local
* _**git add**_, perintah untuk menambahkan file baru, atau perubahan
pada file pada staging sebelum proses commit. 
* _**git commit**_, perintah untuk menyimpan perubahan kedalam database git. 
* _**git push -u origin master**_, perintah untuk mengirim perubahan pada repository 
local menuju server repository. 
* _**git clone [url]**_, perintah untuk membuat working directory yang diambil dari 
repositry sever.
* _**git remote add origin [url]**_, perintah untuk menambahkan remote 
server/reopsitory server pada local repositry (working directory)

# Cara Membuat Repository Online <h2>
* Lakukan Login ke [Github](https://github.com)
* Buatlah Directory Dengan Cara Klik `Create A New Repository`
![Github Logo](https://github.com/SyahriRahmat/Latihan1/blob/master/2.png) <h6> 


# Cara Membuat Repository Local <h2>

* Buka Sebuah Directory, misal : `/dev/sda/Latihan1`
* Masuk ke directory yang sudah dibuat sebelumnya, `/dev/sda/Latihan1`
* Lakukan git init pada directory tersebut
* Buat File dengan nama README.md dengan cara :
![Github Logo](https://github.com/SyahriRahmat/Latihan1/blob/master/1.png) <h6>
* Lakukan commit dengan cara, `git commit -m "first commit"`
* lakukan remote dengan cara, `git remote add origin [url]`
* Lakukan push dengan cara, `git push -u origin master`
* Masukkan Username dan Password Github
* Lihat Hasilnya di Github dengan cara _Refresh (Muat Ulang) halaman Github_
![Github Logo](https://github.com/SyahriRahmat/Latihan1/blob/master/4.png) <h6>
