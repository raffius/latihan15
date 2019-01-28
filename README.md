# latihan15


langkah-langkah cara penggunaan git hub
gambar1

Apa itu git Git adalah pengontrol versi yang bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

Langkah-langkah Install GIT di berbagai jenis sistem
Install GIT di Windows

Menginstall GIT di Windows sangat mudah, cukup dengan mendownload dan menjalankan instalasinya. Ikuti langkah berikut ini untuk meng-install GIT di Windows:

1.Buka website ini dan download installer GIT untuk Windows. 2.Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua proses instalasi selesai.

PERINTAH DASAR GIT
git init, perintah untuk membuat repository local
git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
git commit, perintah untuk menyimpan perubahan kedalam database git.
git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.
git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).
Langkah-Langkah Menggunakan Git
Klik kanan pada monitor Klik " Git Bash Here"

![1930](https://user-images.githubusercontent.com/46749109/51827554-49756e80-231c-11e9-9560-5fc5f7d39e4d.jpg)

Maka akan ada tampilan command prompt seperti dibawah ini

gambar3

Buka Drive yang ingin dipakai, semisal Drive D jalankan dengan perintah cd /d

gambar4

Buat directory dengan printah "mkdir" sebagai contoh : directory Pemograman1

gambar5

Buka directory Pemograman1 dengan perintah cd Pemograman1

gambar6

Buat directory latihan1 dan buka directory latihan1.

gambar7

Menambahkan file baru pada repository dengan perintah echo "#latihan1" >> README.md

gambar8

Jalankan perintah git init untuk menjalankan repository local

gambar9

Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add README.md

gambar10

Untuk menyimpan perubahaan yang ada kedalam database repository local, gunakan perintah git commit -m "File pertama saya"

gambar11

Buat repository server, isi nama repositorynya semisal : latihan1 ,kemudian klik tombol Creat repository

gambar12

Menambahkan remote repository. remote repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan sehingga dapat diakses oleh banyak user.

gambar13

Mengirim perubahan ke server dengan perintah git push -u origin master

gambar14

Melihat hasil pada repository, buka laman github.com arahkan pada repositorynya. Maka perubahan akan terlihat pada laman tersebut

gambar15

Buka drive D kemudian klik Pemograman1, klik latihan1

gambar16

Klik kanan pada file Readme.md kemudian pilih aplikasi untuk mengubah file, semisal dibawah ini dengan aplikasi notepad

gambar17

Untuk mengirim perubahan jalan perinta git push -u origin master, kemudian git add README.md dan git commit -m "latihan1"

gambar18

Kemuidan lihat perubahannya pada laman github.com

gambar19

SEKIAN DAN TRIMAKASIH

NAMA : RYAN SEPTIANTO
NIM : 311810417
KELAS : TI 18 B1
