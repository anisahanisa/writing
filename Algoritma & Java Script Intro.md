Algoritma & Java Script Intro
Algoritma adalah angkaian terbatas dari instruksi-instruksi yang rumit, yang biasanya digunakan untuk menyelesaikan atau menjalankan suatu kelompok masalah komputasi tertentu. Algoritma digunakan sebagai spesifikasi untuk melakukan perhitungan dan pemrosesan data. Atau dengan kata lain algoritma adalah sebuah kegiatan yang sudah kita terapkan dalam kehidupan sehari hari, proses tersebut dilakukan dengan cara yang logis atau masuk akal dan sistematis atau terurut.
Kenapa sih algoritma sangat penting untuk dipelajari? Padahal dalam dunia keseharian kita sudah menerapkan algoritma, karena seorang programming itu justru identic dengan memecahkan masalah atau problem solving, maka dari itu algoritma merupakan pemeran utama dalam membantu memecahkan masalah dan juga algoritma menjadi penghatar bagi teman teman IT dan non IT untuk menjelaskan cara menyelesaikan masalah yang ada.
Ciri ciri algoritma antara lain sebagai berikut: 
a.	Input (memiliki 0 atau lebih inputan)
b.	Output (memiliki min 1 buah output)
c.	Definiteness (intruksi jelas tidak ambigu)
d.	Finiteness (memiliki titik berhenti stop)
e.	Effectiveness (sebisa mungkin tepat sasaran dan efisien)
Jenis jenis algoritma antara lain sebagai berikut:
1.	Seguence (instruksi yang dijalankan secara berurutan)
2.	Selection (instruksi yang dijalankan jika memenuhi sesuatu)
3.	Iteration (instruksi yang berulang kali dijalankan selama memenuhi sesuatu kondisi)
4.	Concurrent (instruksi yang dijalankan secara bersamaan)
Algoritma dapat ditugaskan dengan berbagai cara algoritma antara lain:
a.	Deskriptif (penulisan dengan cara ini seperti kita menulis tutorial dengan bahasa sehari – hari)
b.	Flow chart (penyajiannya lebih mudah di baca karena memiliki tampilan visual, dan menggunakan symbol bangun datar sebagai representasi dari proses yang di lakukan)
c.	Pseudo code (penulisan algoritma yang hamper menyerupai penulisan pada kode pemrograman disebut dengan pseudo code)
Java script introduction
	Java script adalah bahasa pemograman yang sangat powerful yang digunakan untuk logic pada sebuah website. Javascript juga dapat membuat website menjadi interaktif dan dinamis.
Dan untuk menjalankan javascript yaitu klik kanan dan klik inspect element setelah itu ada bagian atas yaitu console nah disini kita bisa menulis javascript di sini tanpa harus membuat visual studio code, sekarang kita coba menggunakan dengan vscode langsung
Yang pertama seperti biasa kita membuat file lalu kita buka menggunakan bash code lalu code dalam bashnya terus untuk menggunakan javascript kita menggunakan index.html terlebih dahulu lalu kita membuat structuk html dan kita pasangkan dengan javascript sebelum di pasangkan kita membuat file js terlebih dahulu lalu kita tempelin. Nah kalau untuk tes jsnya kita perlu menggunakan html.
Setelah itu kita buat variable di js let name= “alpha” console.log(name) setelah itu bagaimana nih untuk tampilinnya nah kita tampilin dengan menggunakan hmtl seperti biasa lalu klik kanan ke inspect element nah terus kita klik bagian console sekarang udah keliatan deh variable yang kita buat.
Dan sekarang kita mau menukar isi variable tanpa membuat variable lainnya, di dalam js ad acara cepetnya yaitu kita melakukan destructur js dengan contoh:
let A = “kopi”
 let B = “the”
 [A, B] = [B, A]
 console.log(A) 
console.log (B)
Cara Menyisipkan Javascript
Ada dua cara, yaitu:
1.	Internal JavaScript, yaitu menyisipkan kode JavaScript langsung di dalam file HTML.
2.	External JavaScript, yaitu membuat file JavaScript sendiri dan menyambungkannya dengan file HTML.
•	Internal Javascript
Untuk menyisipkan kode JavaScript di dalam file HTML, kita bisa menuliskan kode JavaScript di dalam tag <script>. Tag <script> sendiri bisa ditulis di dalam <head> maupun di dalam bagian akhir dari <body>.

•	Eksternal Javascript
Cara menyambungkannya sama seperti internal JavaScript, yaitu menggunakan tag <script> di dalam element <body>, hanya saja, kita menambahkan attribute src di dalam <script> untuk menyambungkan dengan file eksternal JavaScript kita.



Mendeklarasikan Variabel
Cara mendeklarasikan sebuah variabel adalah dengan kata kunci var, let atau const dan diikuti dengan nama variabelnya, seperti ini:
•	var namaVariabel1 = "hallo";
•	let namaVariabel2 = "hello";
•	const namaVariabel3 = "world";
Note : untuk penulisan dengan var sudah jarang digunakan dan tidak disarankan
Dalam menamakan variabel, perlu mengikuti beberapa ketentuan sebagai berikut:
1.	Menggunakan konvensicamelCase, yaitu menggunakan huruf kecil pada permulaan kata, dan jika nama variabel terdiri dari 2 kata atau lebih, maka kata kedua dan berikutnya diawali dengan huruf besar.
2.	Nama variabel boleh diawali dengan underscore(_), huruf besar (jika diharuskan), dan $.
3.	Nama variabel tidak diawali dengan angka, @, *, #, !, %, (), -, +.
4.	Tidak boleh menggunakan kata kunci JavaScript seperti boolean, break, else, extends, dan lain-lain.
5.	Antara kata pertama dan kata kedua tidak diberi spasi atau dash(-);
6.	Karena JavaScript bersifat case-sensitive, maka penamaan juga case-sensitive (jadi variabel hitung dengan variabel Hitung itu berbeda).
Tipe Data Javascript
Berikut beberapa tipe data dalam Javascript
	String, deretan karakter yang diapit oleh sepasang tanda kutip.
	Number, bilangan bulat, pecahan, dan lain-lain.
Note: Dalam tipe data number ini dibagi lagi :
	integer (seperti 1, 2, dan 3)
	atau float (seperti 3.14, 2.718, dan 1.618)
	Boolean, nilai benar dari sebuah pernyataan yang dituliskan sebagai true atau false.
	Null, sebuah nilai yang berarti kosong atau menunjuk pada nilai yang tidak ada.
	Undifined, berbeda dari null, undefined menandakan kondisi variabel yang belum diberi sebuah nilai. Jadi pernyataan "nilai variabel itu adalah undefined" sebenarnya kurang tepat, sebab variabelnya memang tidak mempunyai sebuah nilai.
	Object, sebuah kumpulan pasangan properti dan nilai
	Array, adalah tipe variabel yang dapat menampung berbagai jenis data dengan tipe yang bermacam-macam, dengan jumlah yang tidak terbatas.
Operator Aritmatika
Operator aritmatika digunakan di operasi matematika yang melibatkan data dengan tipe number.
Operator-operator tersebut dapat dilihat pada tabel berikut ini:
+	=   Penjumlahan
-	=   Pengurangan
*	=   Perkalian
/	=   Pembagian
**	=   Eksponen (pangkat)
%	=   Modulus (menghasilkan sisa hasil pembagian)
++	=   Increment (menambah 1)
--	=   Decrement (mengurangi 1)

Operator Logika
Operator logika digunakan untuk menentukan logika antara dua kondisi atau nilai.
Operator        Deskripsi
&&	            AND (Dan)
||	            OR (Atau)
!	            NOT (Bukan)
Tabel perbandingan:
Operator	       Kondisi 1	      Kondisi 2	Hasil
&&	          true	        true	       	 true
&&	          true	        false	 false
&&	          false	        true	                false
&&	          false	        false	 false
||	          true	        true	                true
||	          true	        false	 true
||	          false	        true	                true
||	          false 	        false	 false
!	          true	          -	                false
!	          false	          -	                true

Javasxript Control Flow 
	Conditional merupakan statement percabangan yang menggambarkan suatu kondisi.
	Conditional statement akan mengecek kondisi spesifik dan menjalankan perintah berdasarkan kondisi tersebut
	Perintah akan dijalankan jika hanya kondisi bernilai true.
Looping
	Looping adalah control flow yang mengulang sebuah instruksi/perintah hingga kondisinya terpenuhi atau jika kondisi stop/berhenti tercapai.
	Looping biasanya digunakan untuk mempersingkat penulisan kode sehingga menghemat waktu.
Berdasarkan penjelasan diatas cukup terlihat perbedaan antara conditional dan looping. Berikut ini terdapat beberapa conditional dan looping yang ada pada Javascript
Conditional
•	if
Digunakan apabila hanya ada 1 kondisi dan 1 keputusan yang dijalankan.
if (kondisi1) {
  // masukkan kode yang akan dijalankan di sini apabila kondisi1 tercapai
}
•	if ... else
Digunakan apabila ada 1 kondisi dan 2 keputusan yang dijalankan.
if (kondisi1) {
  // masukkan kode yang akan dijalankan di sini apabila kondisi1 tercapai
} else {
  // masukkan kode yang akan dijalankan di sini apabila kondisi1 TIDAK tercapai
}
•	if ... else if ...
Digunakan apabila ada beberapa kondisi dan beberapa keputusan yang dijalankan.
if (kondisi1) {
  // masukkan kode yang akan dijalankan di sini apabila kondisi1 tercapai
} else if (kondisi2) {
  // masukkan kode yang akan dijalankan di sini apabila kondisi1 tidak tercapai dan kondisi2 tercapai
} else if (kondisi3) {
  // masukkan kode yang akan dijalankan di sini apabila kondisi1 dan kondisi2 tidak tercapai, dan kondisi3 tercapai
} else {
  // masukkan kode yang akan dijalankan di sini apabila semua kondisi di atas TIDAK tercapai
}
•	switch case
Jika kita memiliki banyak pilihan kondisi, menggunakan perintah if, else if dan else akan kurang efisien karena kode yang ditulis akan menjadi sangat panjang sekali.
Alternatifnya adalah menggunakan switch dan case
switch (pernyataan) {
  case kondisi1:
    // keputusan yang dijalankan ketika kondisi1 tercapai
    break;
  case kondisi2:
    // keputusan yang dijalankan ketika kondisi2 tercapai
    break;
  case kondisi3:
    // keputusan yang dijalankan ketika kondisi3 tercapai
    break;
  ...
  default:
    // keputusan yang dijalankan ketika semua kondisi tidak tercapai
}
o	switch digunakan untuk mendeklarasikan pernyataan yang menjadi patokan kondisi.
o	case digunakan untuk menulis masing-masing kondisi dari hasil pernyataan yang akan diperiksa.
o	break digunakan untuk menghentikan program berjalan ketika sudah menemukan kondisi yang tercapai.
o	default adalah keputusan yang akan dijalankan apabila hasil pernyataan di switch tidak ada yang sesuai dengan masing-masing kondisi di case (tidak ada kondisi yang tercapai).
Loopping
•	for loop
For loop merupakan instruksi pengulangan yang dapat kita berikan pada program yang kita kembangkan.
Gunakan for loop jika kita tahu seberapa banyak nilai pasti untuk pengulangannya
for (initialization; condition; post-expression) {
  // statement
}
	Inisialisasi: Sebagai inisialisasi awal dari mana mulainya sebuah pengulangan. Kita memberikan nilai awal/default pada parameter ini.
	Condition: For loop akan terus berjalan selama kondisi ini terpenuhi. Selama kondisi bernilai TRUE.
	Post-expression (Increment/Decrement): Iterasi statement yang digunakan untuk mengupdate variabel yang menjadi kontrol pada pengulangan.
•	while loop
While loop akan menjalankan instruksi pengulangan kondisi bernilai TRUE.
Gunakan while loop jika kita tidak mengetahui jumlah pasti pengulangan.
while (expression) {
  // statement
}
•	do while loop
Do while akan melakukan pengulangan sebelum dilakukan pengecekan kondisi.
do {
  statement(s);
} while(expressions);


 
