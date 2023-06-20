<div align="center">
  
# GIT DAN GITHUB

</div>

![cover!](cover_git.png)
## APA ITU GIT DAN GITHUB
Git dan GitHub adalah dua platform yang berhubungan dengan version control system (VCS), yaitu sebuah sistem yang dapat mencatat semua perubahan kode pada project. Git adalah alat version control yang digunakan untuk mengolah kode script secara offline melalui jaringan LAN. Git memungkinkan pengguna untuk melakukan perubahan dan penggabungan kode serta mencatat riwayat perubahannya¹. GitHub adalah alat version control sekaligus penyimpanan cloud yang berbasis repositori Git. GitHub berfungsi sebagai tuan rumah terhadap repositori Git dalam penyimpanan kode di lokasi yang terpusat¹. GitHub juga menyediakan fitur project manajemen, diskusi, review code, dan lain-lain.

## KENAPA BELAJAR GIT?
Ada beberapa alasan kenapa kamu harus belajar Git, yaitu:

- Git memungkinkan kamu untuk melakukan proyek kolaborasi secara online melalui sistem cloud¹. Kamu bisa berbagi kode, melakukan review, diskusi, dan penggabungan kode dengan anggota tim lainnya².
- Git menyimpan semua perubahan kode dalam database yang terdistribusi³. Kamu bisa melihat riwayat perubahan, kembali ke versi sebelumnya, atau mencari kode yang hilang dengan mudah⁴.
- Git adalah teknologi yang sudah menjadi barometer sistem pengembangan perangkat lunak pada perusahaan besar di dunia¹. Jika kamu bisa menggunakan Git, kamu akan memiliki nilai tambah sebagai programmer profesional.
- Git mempercepat proses review perangkat lunak dan mendukung budaya agile development¹. Kamu bisa menggunakan fitur seperti branch, fork, pull request, dan merge untuk mengelola kode dengan lebih efisien dan fleksibel.
- Git memungkinkan kamu untuk menyimpan hasil pekerjaanmu secara online¹. Kamu bisa membuat portofolio atau berkontribusi ke proyek open source dengan menggunakan GitHub, salah satu platform berbasis Git yang populer.

## CARA INSTALL GIT DI WINDOWS
Berikut ini adalah panduan instalasi Git di Windows:

- Kamu bisa mengunduh file installer Git di situs resmi https://git-scm.com/downloads sesuai dengan versi Windows yang kamu gunakan (32-bit atau 64-bit).
- Setelah proses download selesai, kamu bisa klik dua kali file instalasi Git yang telah kamu unduh dan mengikuti petunjuk instalasi.
- Ada beberapa pilihan yang harus kamu perhatikan saat instalasi, seperti:

  - Lokasi instalasi: Kamu bisa memilih lokasi direktori yang kamu inginkan atau biarkan default.
  - Komponen yang dipilih: Kamu bisa memilih komponen tambahan yang ingin kamu install atau biarkan default.
  - Path environment: Kamu bisa memilih opsi yang tengah agar perintah Git dapat dikenali di Command Prompt (CMD) atau PowerShell.
  - Editor default: Kamu bisa memilih editor teks yang ingin kamu gunakan untuk Git atau biarkan default.
  - Line ending conversion: Kamu bisa memilih opsi konversi line ending yang sesuai dengan kebutuhanmu atau biarkan default.
  - Terminal emulator: Kamu bisa memilih opsi terminal emulator yang ingin kamu gunakan untuk Git Bash atau biarkan default.
  - Behavior of git pull: Kamu bisa memilih opsi behavior of git pull yang sesuai dengan kebutuhanmu atau biarkan default.

- Setelah selesai instalasi, kamu bisa membuka Command Prompt atau PowerShell dan mengetik git --version untuk memeriksa versi Git yang terinstal.

## CARA INSTALL GIT DI LINUX
Berikut ini adalah panduan instalasi Git di Linux:

- Kamu bisa menginstall Git menggunakan package manager yang tersedia di distro Linux yang kamu gunakan. Misalnya, jika kamu menggunakan Debian atau Ubuntu, kamu bisa menggunakan perintah sudo apt install git. Jika kamu menggunakan Fedora, kamu bisa menggunakan perintah yum install git. Setelah itu, kamu bisa mengetik git --version untuk memeriksa versi Git yang terinstal.
- Kamu juga bisa menginstall Git dari source code jika kamu ingin mendapatkan versi terbaru atau mengkustomisasi opsi instalasi. Untuk itu, kamu harus mengunduh source code Git dari situs resmi https://git-scm.com/download. Setelah itu, kamu harus menginstal beberapa dependensi yang dibutuhkan untuk kompilasi. Kemudian, kamu bisa mengekstrak file source code dan menjalankan perintah make configure untuk membuat file konfigurasi. Selanjutnya, kamu bisa menjalankan perintah ./configure --prefix=/usr/local untuk menentukan lokasi instalasi. Lalu, kamu bisa menjalankan perintah make all doc info untuk mengkompilasi source code dan dokumentasinya. Terakhir, kamu bisa menjalankan perintah sudo make install install-doc install-html install-info untuk menginstal Git dan dokumentasinya.

## CARA INSTALL GIT DI MAC
Berikut ini adalah panduan instalasi Git di Mac:

- Kamu bisa menginstall Git dengan beberapa cara, seperti menggunakan Xcode Command Line Tools, Homebrew, atau file installer dari situs resmi https://git-scm.com/download/mac.
- Jika kamu menggunakan Xcode Command Line Tools, kamu bisa mengetik perintah xcode-select --install di Terminal dan mengikuti petunjuk instalasi. Jika kamu belum memiliki Xcode, perintah ini akan mengunduh dan menginstall Xcode beserta Git.
- Jika kamu menggunakan Homebrew, kamu bisa mengetik perintah brew install git di Terminal dan menunggu proses instalasi selesai. Jika kamu belum memiliki Homebrew, kamu bisa mengunduh dan menginstallnya dari situs resmi https://brew.sh/.
- Jika kamu menggunakan file installer, kamu bisa menjalankan file tersebut dan mengikuti petunjuk instalasi. Kamu bisa memilih opsi yang sesuai dengan kebutuhanmu saat instalasi.
- Setelah selesai instalasi, kamu bisa mengetik git --version untuk memeriksa versi Git yang terinstal.

## BAGAIMANA MEMULAI GIT
Berikut ini adalah panduan untuk memulai Git:

- Kamu harus menginstall Git terlebih dahulu di perangkat yang kamu gunakan. Kamu bisa mengikuti tutorial instalasi Git di Windows, Linux, atau Mac yang sudah kami jelaskan sebelumnya.
- Kamu harus membuat akun di salah satu platform berbasis Git, seperti GitHub, GitLab, atau Bitbucket. Kamu bisa mendaftar secara gratis dan mendapatkan akses ke berbagai fitur dan repositori.
- Kamu harus mengkonfigurasi Git dengan menggunakan perintah git config --global user.name \"nama_kamu\" dan git config --global user.email \"email_kamu\" di terminal atau command prompt. Pastikan nama dan email kamu sesuai dengan akun yang kamu buat di platform Git.
- Kamu harus membuat repositori Git, yaitu tempat untuk menyimpan dan mengelola kode. Kamu bisa membuat repositori lokal di perangkat kamu dengan menggunakan perintah git init di folder yang kamu inginkan¹². Kamu juga bisa membuat repositori remote di platform Git dengan menggunakan fitur yang disediakan.
- Kamu harus menambahkan file ke repositori Git dengan menggunakan perintah git add nama_file atau git add . untuk menambahkan semua file¹². Perintah ini akan menambahkan file ke staging area, yaitu tempat untuk menyimpan file yang siap untuk dicommit.
- Kamu harus membuat commit, yaitu tanda atau label untuk setiap perubahan kode. Kamu bisa menggunakan perintah git commit -m \"pesan_commit\" untuk membuat commit dengan pesan yang menjelaskan perubahan yang kamu lakukan. Perintah ini akan menyimpan file dari staging area ke repositori lokal.
- Kamu harus melakukan remote, yaitu menghubungkan repositori lokal dengan repositori remote. Kamu bisa menggunakan perintah git remote add origin url_repositori_remote untuk menambahkan remote dengan nama origin. Perintah ini akan memungkinkan kamu untuk berkomunikasi dengan repositori remote.
- Kamu harus melakukan push, yaitu mengirimkan file dari repositori lokal ke repositori remote. Kamu bisa menggunakan perintah git push -u origin nama_branch untuk melakukan push ke branch yang kamu inginkan. Perintah ini akan mengupload file dari repositori lokal ke repositori remote.
- Kamu juga bisa melakukan pull, yaitu mengambil file dari repositori remote ke repositori lokal. Kamu bisa menggunakan perintah git pull origin nama_branch untuk melakukan pull dari branch yang kamu inginkan. Perintah ini akan mendownload file dari repositori remote ke repositori lokal.

## PERINTAH DASAR GIT

Berikut ini adalah beberapa perintah dasar Git yang sering digunakan:

- git init: Digunakan untuk membuat repositori lokal baru di folder yang kamu inginkan¹²³. Perintah ini akan membuat folder .git yang berisi konfigurasi dan metadata repositori.
- git status: Digunakan untuk mengecek status repositori lokal, seperti file yang berubah, file yang belum ditambahkan, file yang sudah ditambahkan, branch yang aktif, dll. Perintah ini berguna untuk melihat perubahan yang terjadi di repositori lokal sebelum melakukan commit atau push.
- git add: Digunakan untuk menambahkan file ke staging area, yaitu tempat untuk menyimpan file yang siap untuk dicommit¹²³. Kamu bisa menambahkan file secara spesifik dengan nama file, seperti git add nama_file, atau menambahkan semua file dengan tanda titik, seperti git add .
- git commit: Digunakan untuk membuat commit, yaitu tanda atau label untuk setiap perubahan kode. Perintah ini akan menyimpan file dari staging area ke repositori lokal. Kamu harus menambahkan pesan commit dengan opsi -m untuk menjelaskan perubahan yang kamu lakukan, seperti git commit -m \"pesan_commit\".
- git push: Digunakan untuk mengirimkan file dari repositori lokal ke repositori remote. Perintah ini akan mengupload file dari repositori lokal ke repositori remote yang sudah dihubungkan dengan opsi remote add. Kamu harus menentukan nama remote dan nama branch yang ingin kamu push, seperti git push origin master. 
- git pull: Digunakan untuk mengambil file dari repositori remote ke repositori lokal[^1^. Perintah ini akan mendownload file dari repositori remote ke repositori lokal dan menggabungkannya dengan branch yang aktif. Kamu harus menentukan nama remote dan nama branch yang ingin kamu pull, seperti git pull origin master. 
- git clone: Digunakan untuk mengunduh kode sumber dari repositori remote ke repositori lokal. Perintah ini akan membuat salinan identik dari proyek dalam repositori remote dan menyimpannya ke komputer kamu. Kamu harus menentukan URL repositori remote yang ingin kamu clone, seperti git clone https://github.com/user/repo.git. 
- git branch: Digunakan untuk melihat, membuat, atau menghapus branch di repositori lokal atau remote. Branch adalah cabang dari kode sumber yang bisa digunakan untuk mengembangkan fitur baru atau memperbaiki bug tanpa mengganggu branch utama. Kamu bisa melihat semua branch yang ada dengan perintah git branch --list, membuat branch baru dengan perintah git branch nama_branch, atau menghapus branch dengan perintah git branch -d nama_branch. 
- git checkout: Digunakan untuk berpindah antara branch di repositori lokal atau remote. Perintah ini akan mengubah konten direktori kerja sesuai dengan branch yang dipilih. Kamu harus menentukan nama branch yang ingin kamu checkout, seperti git checkout nama_branch[^1^. Kamu juga bisa membuat dan checkout branch baru sekaligus dengan opsi -b, seperti git checkout -b nama_branch_baru. 
- git merge: Digunakan untuk menggabungkan dua atau lebih branch menjadi satu branch. Perintah ini akan mencoba menggabungkan perubahan kode dari branch lain ke branch aktif secara otomatis, tetapi bisa juga menyebabkan konflik jika ada perbedaan kode yang tidak bisa diselesaikan oleh Git. Kamu harus menentukan nama branch yang ingin kamu gabungkan, seperti git merge nama_branch_lain.


