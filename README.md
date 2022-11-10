GIT&GITHUB LANJUTAN 
Git adalah tools untuk programmer, sebagai version control system dan tugasnya adalah mencatat setiap perubahan file termasuk code yang kita buat pada project secara individu ataupun team. File file yang disimpan menggunakan git akan terlacak seluruh perubahannya termasuk siapa yang mengubah.
Contoh membuat repository
git init .(nama project)
berfungsi untuk membuat direktori baru
setelah itu check git status 
apakah repository masih di awal atau sudah di berada yang kita buat
setelah itu kita ubah untrackted file dan unmodified menjadi modified menggunakan git add
git add .
setelah itu lakukan git commit untuk save perubahan dalam version control 
git commit -m
jika ada revisi dari team kita sediri bisa melihat dengan menggunakan git log
yang pertama git log (akan keluar semua yang direvisi)
yang kedua git log - -online (untuk git log lebih pendek)
untuk mengetahui cek perubahan menggunakan 
git diff
untuk membatalkan perubahan yang belum di stagged dan belum commited
git checkout
untuk membatalkan perubahan sudah stagged namun belum commited
git reset
jika kita membatalkan semua perubahan yang ada tanpa menghapus git commit terakhir menggunakan git revert karena kalau menggunakan git reset, commit terakhir akan terhapus
git revert -n <nomor comit>
selanjutnya adalah git branch fitur wajib digunakan jika melakukan berkolaborasi dengan developer atau dalam tim untuk menghindari conflict code yang dikembangkan kita tidak boleh berkolaborasi dalam project di satu branch yang sama. Printah membuat git branch
git branch <nama yang dibuat>

selanjutnya git Merge setelah melakukan branch baru lalu lakukan commit saat kita menyatukan pekerjaan ke master file/branch utama yaitu branch master
yang pertama kita git checkout dari branch master
lalu lakukan marge, git marge <yang kita buat>

RESPONSIVE WEB DESIGN
Apa itu responsive web design? Responsive web design (RWD) adalah bertujuan untuk membuat design website kita dapat diakses dalam device apaun. Dalam membuat aplikasi kita harus memikirkan user yang menggunakannya. Device yang umumnya digunakana adalah laptop/PC, smartphone, dan tablet.
Setiap developer website wajib menggunakan tools bawaan dari setiap browsernya dan setiap browser yang memudahkan proses development website.
Cara setting up chrome dev tools 
1.	Untuk Windows = ctrl + shift + J
2.	Untuk MAC = ctrl + shift + M
Dan untuk melihat apakah ikon tersebut bisa responsive atau tidak bisa melihat gambar yang seperti tablet dan handphone.
Boostrap
Untuk boostrap kitab isa masukan tamplet tamplet yang sudah di sedaikan boostrap sangat memudahkan para d
