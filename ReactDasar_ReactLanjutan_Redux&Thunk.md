React JS Dasar
Sebuah framework view libarary js untuk membuat tampilan user interface pada website, react JS dikembangkan oleh Jordan Walke pada tahun 2013 yang merupakan seorang developer Facebook dan react JS salah satu framework untuk bagian front-end.
React JS sangat memudahkan aplikasi front-end menjadi lebih cepat walaupun harus menghandle berbagai data dan didalam react dapat menerapkan konsep modular javascript, react js membagai 1 tampilkan pada website menjadi komponen-komponen kecil. Serta dapat menggunakan pada aplikasi berskala kecil hingga besar dan kompleks.
Membuat user interface menggunakan vanilla JS & DOM
Vanilla JS a anonymous menggunakan native javascript (default)
JSX adalah syntax extension for javascript untuk digunakan pada react JS. JSX perlu decompile untuk menjadi javascript jadi sebelum ditampilkan pada browser JSX akan dicompile menjadi javascript terlebih dahulu. Dengan JSX bisa menggunakan HTML di didalam file extansion javascript (js).
Kenapa Menggunakan React Js?
A.	React Js is FAST
React Js membuat aplikasi front-end menjadi lebih cepat walaupun harus menghandle berbagai data.
B.	React Js is MODULAR
Kita dapat menerapkan konsep Modular javascript pada React Js. React Js membagi tampilan pada website menjadi komponen-komponen kecil.
C.	React Js is Scalable
React Js dapat digunakan pada aplikasi beskala kecil hingga besar dan kompleks.
D.	React Js is Popular
Komunitas React Js di seluruh dunia sangat besar. Kebanyakan perusahaan teknologi pun sudah menggunakan React Js.
E.	React Js is component based
F.	React Js is also support build mobile app in React Native
React Component
•	Component adalah salah satu core dari React Js dengan membagi UI dalam satuan-satuan kecil.
•	Component dibuat jika component tersebut bersifat reuseable code (bisa digunakan kembali).
•	Didalam sebuah react kita dapat membuat sebuah component seperti element HTML dengan menggunakan function.
•	React Component memiliki dua jenis yaitu class dan funtional.
•	Class Component adalah react component yang penulisannya menggunakan syntax ES6 class dan didalam class component kita dapat menggunakan state dan props, class component merupakan versi awal dari react component dan sekarang sudah jarang digunakan.
•	Function Component adalah react component yang penulisannya menggunakan format function, pada awalnya kita hanya dapat menggunakan props didalam functional component akan tetapi setelah adanya hooks kita dapat menggunakan props dan state, functional component merupakan react component yang paling dianjurkan untuk digunakan sekarang ini.
State & Props
	State & Props adalah hal yang berhubungan dengan Stateless dan Stateful Component.
	Stateless berarti tidak memiliki State. Dia hanya memiliki props.
	Stateful berarti memiliki state dan bisa mengirim state tersebut ke component.
React Js Lanjutan
React Lifecycle
	Lifecycle didalam react memiliki tiga alur utama
	Mounting adalah sebuah siklus pertama ketika aplikasi dibuka.
	Update adalah sebuah siklus ketika terjadi perubahan data.
	Unmount adalah siklus setelah komponen dibuka.
	Sebelum versi 16 atau adanya Hooks untuk memanipulasi Lifesycle didalam React harus menggunakan
o	componentDidMount();
o	componentWillUpdate();
o	componentWillUnMount();
	Sedangkan untuk versi 16 setelah Hooks sampai sekarang kita dapat menggunakan useEffect() untuk menghandle Lifecycle didalam React.
Form
	Pada react form ini kita akan banyak menggunakan event handler. 
	Seperti onChange() & onSubmit().
	onChange(), digunakan untuk mengambil data/perubahan dari inputan. Sedangkan onSubmit(), digunakan untuk mengsubmit data pada form agar bisa diolah.
	Selain itu kita bisa menambahkan data ke API dengan menggunakan axios.
Hooks
	Hooks merupakan fitur baru di React 16.8. Fitur ini memungkinkan Anda menggunakan state dan fitur React lainnya tanpa menuliskan sebuah kelas. Hooks menggunakan konsep Functional Component.
	Hooks adalah fungsi spesial yang memungkinkan Anda “terhubung” dengan fitur-fitur di React. Sebagai contoh, useState adalah sebuah Hook yang memungkinkan Anda memberi state pada function components.
	Ada beberapa Hooks yang disediakan oleh react, berikut hooks yang paling populer dan sering digunakan

o	useState() adalah hook yang digunakan untuk membuat dan memanipulasi sebuah state.
o	useEffect() adalah hook yang digunakan untuk menghandle lifecycle.
o	useRef() adalah hook untuk memanipulasi elemen DOM.
o	useContext adalah hook untuk memanipulasi sebuah Context API.
o	Dll
o	
React Router
React Router merupakan standar library untuk routing pada React. Standar routing berfungsi untuk membuat suatu website menjadi dynamic. Pada React, Router membantu untuk mengarahka page satu ke page yg lainnya berdasarkan path url yg ditentukan. Instalasi React Router React berisi tiga paket berbeda untuk perutean:
i.	react-router: Ini menyediakan komponen dan fungsi perutean inti untuk aplikasi React Router.
ii.	react-router-native: Ini digunakan untuk aplikasi seluler.
iii.	react-router-dom: Digunakan untuk desain aplikasi web.
Ada dua jenis komponen router:
	<BrowserRouter>: Ini digunakan untuk menangani URL dinamis.
	<HashRouter>: Ini digunakan untuk menangani permintaan statis.
Browser Router merupakan interface pada umumnya yg digunakan untuk menjalankan react di browser atau untuk membuat router-router sederhana.
HashRouter penulisannya menggunakan #, yg digunakan pada sebuah website yang menggunakan satu page saja.
3 cara penggunaan router:
i.	Routing Dasar
ii.	Dynamic Route
iii.	Nested Route
React Redux
Redux digunakan untuk mengolah state management Yaitu dengan menyimpan state di satu tempat, sehingga lebih mudah untuk di manage.
Cara kerja Redux:
	Action: Adalah sebuah function yang mereturn sebuah objek.
	Reducer: sebuah fungsi yang tugasnya untuk mengolah state yang ada di store.
	Store: tempat untuk menampung state

Redux Thunk
	Redux Thunk adalah middleware yang memungkinkan Anda memanggil pembuat aksi yang mengembalikan fungsi sebagai ganti objek aksi.
	Fungsi itu menerima metode pengiriman penyimpanan, yang kemudian digunakan untuk mengirim aksi sinkron di dalam isi fungsi setelah operasi asinkron selesai.









 
