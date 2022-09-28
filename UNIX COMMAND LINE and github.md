UNIX COMMAND LINE

Shell adalah sistem operasi CLI yang bertugas untuk memproses semua perintah yang diketik di CLI. Shell juga akan membaca dan mengartikan perintah, kemudian memberikan instruksi pada sistem operasi untuk menjalankan tugas sesuai permintaan. 

Apa yang dimaksud command line interface??

user bisa mengetikkan perintah dalam bentuk teks dan memberikan instruksi pada komputer untuk mengerjakan tugas tertentu. Dan apa sih bedanya user menggunakan file expoler?  Perbedaan dari keduanya adalah sebegai berikut:

Command Line Interface

1) Cukup kompleks dalam penggunaannya harus memiliki pengetahuan yang baik tentang perintah. Perintah yang salah eja dapat menimbulkan error.
1) Command line interface tidak memerlukan lebih banyak memori karena hanya berupa barisan text.
1) Command Line Interface terbilang cepat, Karena hanya berupa teks aja.

Graphic User Interface

1) GUI tidak perlu memiliki pengetahuan yang luas tentang ilmu komputasi atau coding untuk menggunakannya bahkan seorang pemulapun dapat menggunakannya dengan mudah menangani tugas menggunakan GUI.
1) GUI membutuhkan lebih banyak memori karena mengandung banyak komponen grafis seperti gambar, ikon dan lain lain
1) GUI cenderung lambat karena banyak element grafis yang perlu diload.

Itulah salah beberapa perbedaan dari CLI dan GUI akan tetapi tujuan penggunaanya tetalah sama. 

Disini aku akan menjeleskan tentang bagaimana cara untuk mengakses command line interface ke terminal dan bagaiamana navigasi dalam menggunakan CLI 

1. download “git GUI” setelah download dan sudah terinstal bisa di check di bagian percarian yaitu “GIT BUSH” dan akan tampil seperti CMD itu artinya instalilasinya sukses.
1. Setelah itu kita butuh perintah command pwd (Print Working Directory) untuk mengetahui dimana kita berada contohnya “c/user/anisah”
1. Setelah itu kita butuh sebuah perintah command ls (list) untuk mengetahui apa saja isi direktori milik kita sendiri.
1. Jika kita merasa melihat tampilan git bush teralu banyak dan membuat seorang pula cukup pusing kita bisa menggunakan perintah command clear untuk membersihkan tampilan dan kembali tampilan awalnya.
1. Bagaimana sih cara untuk pindahkan sebuah directory yang awalnya berada di C menjadi directory D, kita hanya membutuhkan perintah command cd (change directory) “ cd D; ” sekarang kita sudah berada directory D.
1. Setelah itu jika kita mau masuk dalam sebuah folder dalam directory D contohnya “/d skilvul” 
1. Setelah itu jika kita ingin keluar dalam folder tersebut kita hanya menambahkan titik dalam perintah command cd contohnya “cd..”
1. Jika kita ingin membuat foldernya tidak terlihat atau hidden kita perlu menambahkan command -a 
1. Cara bagiamana kita membuat folder baru yaitu kita membutuhkan perintah command yaitu “mkdir” (make directory) contohnya mkdir (nama folder) di usahakan nama folder baru jangan menggunakan spasi karena tidak kesulitan.
1. Membuat file didalam folder yang sudah kita buat kita menggunakan perintah command touch contohnya touch (nama file.text) dan untuk mengeditnya kita menggunakan perintah command nano contohnya nano (nama file.text)
1. Bagaimana cara kita melihat isi file menggunakan perintah command cat *(semua isi file ditampil kan)*contohnya cat (nama file.text)
1. Ada 2 perintah command untuk melihat file hanya baris diawal dan akhir menggunakan perintah head(bagian atas) dan tail(bagian bawah).
1. Cara mengcopy file yang memiliki 2 tujuan yaitu file mana yang mau dicopy dan tujuan file mana yang di inginkan menggunakan perintah command cp contohnya (cp tofu.text salin tofu.text) ini adalah contohnya cp untuk copy di tempat yang sama, kalau ingin mengcopy ditempat yang berbeda hanya di perlukan penambahan alamat yang lengkap contohnya (cp tofu.text /d/tofu.text) 
1. Cara pindahkan file yang kita buat menggunakan perintah command mv contohnya mv (nama file) /d/ (nama folder dinginkan) / (nama file yang dipindahkan
1. Bagaiamana cara rename dengan menggunakan perintah command mv contoh mv (nama file yang typo) (nama file yang benar)
1. Cara menghapus perintah command rm contoh rm (*untuk file saja*) (nama file yang ingin di hapus) kalau untuk direktori tambah -d.

GIT & GITHUB

GIT adalah tools untuk progremer, aplikasi yang dapat melacak setiap perubahan yang terjadi perubahan yang terjadi pada suatu folder atau file. Dan git juga biasanya digunakan oleh para programmer sebagai tempat penyimpanan file pemrograman mereka, karena lebih efektif file file yang disimpan menggunakan git akan terlacak seluruh perubahannya, termasuk siapa yang mengubah sepandai apapun programmer tidak akan pernah bisa bekerja sendirian selamanya.

Setup awal buka  git bash teman teman lalu ikuti printah seperti ini

Git config –global user.name anisahanisa

Git config –global user.email <nisaanisah1206@gmail.com>

Setelah itu untuk mengetahui apakah instalasinya berhasil atau engga kita menggunakan perintah command git config – list, jika sudah berhasil bagaimana sih cara keluar dari tampilan seperti ini kita hanya membutuhkan :+Q

Oke setelah itu kita akan membuat suatu folder baru yang di tofu yaitu folder belajar nah didalam folder belejar ini kan tidak ada file atau apapun jadi kita isi dengan command git init

Contoh git init enter, git init sama seperti sebuah memori card yang kita masukan di sebuah handphone (sama seperti perintah git init) yang dimana hanya 1 saja yang bisa di masukan, jadi kita sudah memasang 1 kali git init dalam project kita.

Setelah itu kita sudah memesang git init dalam project kita, jadi kita bisa melacak perubahan didalam project kita tersebut dengan perintah command git status.

Lalu kita mau didalam project ini kita ada perbuhaanya yaitu kita membuat seuatu file yang Bernama touch aku.md jadi di dalam project ini jika di tambahkan sebuah git akan mampu melecak perbuahan di sekitarnya.

Jika kalian menemukan tulisan Untracked files dalam pengecheckan perubahan file kalian jangan lupa menambahkan perintah command untuk pengelacak perubahan yaitu git add.

Setelah kita memberi tanda sebuah file menggunakan command git add . kita harus memberikan keterangan dengan menggunakan perintah git commit -m “isi pesannya ” setelah itu akan muncul point point nya dan pas kita check dalam git status tidak ada perubahan nih dalam file nya jadi kita klik file belajar lalu kita edit menggunakan command nano setelah itu akan ada perubahan dan kita tandain lagi menggunakan git add. Lalu commit -m “add title”

Dan berhasil di commit (setiap perubahaan harus di commit) dan cara untuk melihat hasil yang udah kita commit git log - -oneline  

Okey sekarang kita check menggunakan command ls akan keluar 2 file yang sudah kita buat lalu kita mau tambahin lagi nih membuat baru touch nama file, setelah itu kita check terlebih dahulu sembelum kita melakukan git add . jadi git status setelah itu git add . dan meberikan git commit -m “add nama file” lalu kita check di git log – - oneline. Nah Sudah muncul sekarang bagaiamana kita pindah ke posisi file yang awal jadi kita menggunakan git checkout dan masukan nilai yang paling bawah, dan jika mau balik lagi posisi yang akhir menggunakan command git checkout master.

Lalu bagaiamana sih untuk mempublish ke git hub, pertama kita login terlebih dahulu lalu kit membuat sebuah repository setelah itu kita memberikan nama file dan ada pilihan private or public lalu creat dan itu kita sambungkan ke git bash “git remote add origin <https://github.com/anisahanisa/belajar-git.git>” setelah itu kita “git push -u origin master” untuk uploadnya


