React Context
 React Context dirancang untuk berbagi data yang dapat diakses oleh banyak komponen tanpa harus mengirimkan props secara manual ke setiap level atau dianggap "global" untuk pohon komponen React, seperti pengguna yang diautentikasi saat ini, tema, atau bahasa pilihan. Context dapat digunakan untuk mengatasi masalah yang sering terjadi dalam React, seperti prop drilling dan membagi state yang berbeda antar komponen. Untuk membuat new context, gunakan fungsi createContext baru React. Fungsi createContext mengembalikan a Provider dan a Consumer component.
Membuat Context
 Context ini dapat dibuat dengan menggunakan `React.createContext()`. Context juga dapat digunakan untuk menyimpan data yang dapat diakses oleh komponen-komponen yang berada di dalamnya.
jsx
  > import React, { createContext } from 'react';
  > export const TodoContext = createContext()
 export default TodoContext;

Menggunakan Context
Context dapat digunakan dengan menggunakan Context.Provider dan Context.Consumer.
Context.Provider digunakan untuk menyediakan data yang dapat diakses oleh komponen-komponen yang berada di dalamnya. Context.Consumer digunakan untuk mengakses data yang disediakan oleh Context.Provider.

 React Testing

Testing berarti memeriksa bahwa kode kita memenuhi beberapa harapan Testing sendiri dibagi menjadi 2 tipe, yaitu manual dan automation Testing automation dibagi menjadi beberapa kategori yaitu:
a)	Unit Testing, bagian terkecil komponen seperti function.
b)	Integration Testing, melakukan testing aplikasi yang saling terhubung satu sama lain (aplikasi dengan database).
c)	End to End, melakukan testing dari sisi user seperti UI.
Terdapat 2 scenario yang dilakukan dalam melakukan unit testing yaitu:
a)	Mewarisi kode warisan yang datang tanpa tes.
b)	Menerapkan fungsi baru secara tiba-tiba.

Alur testing:
a.	import fungsi untuk menguji.
b.	Memberikan masukan ke fungsi.
c.	Menentukan apa yang diharapkan sebagai output.
d.	Memeriksa apakah fungsi menghasilkan output yang diharapkan.
 Tujuan pertama dari testing adalah untuk mencegah regresi. Regresi adalah kemunculan kembali bug yang sebelumnya telah diperbaiki. Itu membuat fitur berhenti berfungsi sebagaimana dimaksud setelah peristiwa tertentu terjadi
a.	Testing digunakan memastikan fungsionalitas komponen kompleks dan aplikasi modular.
b.	Testing diperlukan untuk kinerja yang efektif dari aplikasi perangkat lunak atau produk.
c.	React Testing Library dibangun di atas DOM Testing Library dengan menambahkan API untuk bekerja dengan komponen React.
d.	React Testing Library merupakan cara untuk melakukan testing pada komponen React.
e.	React Testing Library dapat digunakan untuk melakukan testing pada komponen React tanpa harus menguji implementasi detail dari komponen tersebut.












 
