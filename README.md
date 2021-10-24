NAMA: M IRGI FAHREZI

KELAS: TI.21.C5

# PENGGUNAAN GIT
APA ITU GIT ?
Git adalah salah satu sistem pengontrol versi (Version ControlSystem) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds.
Pengontrol versi bertugas mencatat setiap perubahan pada fileproyek yang dikerjakan oleh banyak orang maupun sendiri.
Git dikenal juga dengan distributed revision control (VCS terdistribusi),artinya penyimpanan database Git tidak hanya berada dalam satutempat saja.

INSTALASI GIT

Download Git, buka website resminya Git (git-scm.com).
Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
Selamat, Git sudah terinstal di Windows. Untuk mencobanya,silahkan buka CMD atau PowerShell, kemudian ketik perintah
TUTORIAL MENGGUNAKAN GIT
Perintah Dasar Git

-git init, perintah untuk membuat repository local

-git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.

-git commit, perintah untuk menyimpan perubahan kedalam database git.

-git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.

-git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.

-git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)

-git pull, perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository

Pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi Username dan Email. Jalankan perintah berikut:

$git config --global user.name "username"

$git config --global user.name "email"

<img width="960" alt="pict 3" src="https://user-images.githubusercontent.com/92860414/138260084-27c9773a-6c67-4327-a2e7-81bd25c84c48.png">


$git init

<img width="960" alt="pict 4" src="https://user-images.githubusercontent.com/92860414/138260471-80e56660-16bd-47c8-8719-5b166295de12.png">

Untuk membuat file dapat menggunakan Text Editor, Lalu menyimpan filenya pada repository. Sebagai contoh disini saya akan membuat file README.md dengan perintah berikut

$echo "# Latihan1" >> README.md

Untuk menambahkan file yang sudah kita buat, gunakan perintah git add (Nama File) atau bisa menggunakan git add . (Jika file nya ada banyak)
$git add README.md

<img width="960" alt="pict 5" src="https://user-images.githubusercontent.com/92860414/138260860-a7ef53af-2fca-41f9-8632-6cce5e882da2.png">

Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m "nama project" Dan yang ada di dalam tanda kutip " " itu nama project kita dan jangan sama setiap kali kita upload project

<img width="960" alt="pict 6" src="https://user-images.githubusercontent.com/92860414/138261514-ae12d468-d530-4521-aefe-dad9216d8aa3.png">

$git commit -m "First Project"  Untuk menyimpan setiap perubahan pada repository local, gunakan perintah git remote add origin (url) git remote add origin https://github.com/Ifhrzy022/LatihanVCS

<img width="960" alt="pict 7" src="https://user-images.githubusercontent.com/92860414/138261537-a742f4ad-7ed6-4672-b2a4-9ad0f6aca100.png">

Untuk mengirim perubahan pada repository local ke server, gunakan perintah git push Perintah ini akan meminta Username dan Password pada akun github mu

$git push -u origin master

<img width="960" alt="pict 8" src="https://user-images.githubusercontent.com/92860414/138261300-8370755a-6be3-486c-935b-5d06e3691201.png">

Selesai
 
![image](https://user-images.githubusercontent.com/92860414/138598585-9d0ee739-1da4-474b-b0ad-5e8361c4d820.png)
