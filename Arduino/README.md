<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/5b/Arduino_Logo_Registered.svg"width=300 height=200> <br>
</p>

## 🎉🎉 Selamat Datang di Arduino 🎉🎉
Apa itu Arduino? Apakah kamu pernah mendengar istilah tersebut? Arduino sendiri adalah sebuah perangkat purwarupa (prototyping) yang bersifat open source. Nah, pada artikel kali ini kita akan membahas tentang arduino mulai dari pengertian, kegunaan, komponen, perbandingan dengan perangkat prototype sejenis, hingga kelebihan serta kekurangannya. Jadi, simak artikel ini dengan baik ya agar tidak ada informasi yang terlewatkan.

## 📝 Penjelasan Singkat 📝
Menurut website resmi Arduino, Arduino merupakan sebuah perangkat elektronik yang bersifat open source dan sering digunakan untuk merancang dan membuat perangkat elektronik serta software yang mudah untuk digunakan. Arduino ini dirancang sedemikian rupa untuk mempermudah penggunaan perangkat elektronik di berbagai bidang.

Arduino ini memiliki beberapa komponen penting di dalamnya, seperti pin, mikrokontroler, dan konektor yang nanti akan dibahas lebih dalam selanjutnya. Selain itu, Arduino juga sudah menggunakan bahasa pemrograman Arduino Language yang sedikit mirip dengan bahasa pemrograman C++. 

Biasanya Arduino digunakan untuk mengembangkan beberapa sistem seperti pengatur suhu, sensor untuk bidang agrikultur, pengendali peralatan pintar, dan masih banyak lagi.

_@dikoding_

## 🔧 Komponen Pada Arduino 🔧
<p align="center">
  <img src="https://media2.giphy.com/media/mFDWuDppjQJjite6FS/giphy.gif?cid=ecf05e47kul6glue8fyh89n63yo9j0fcczlfsivsgtp0vlxh&ep=v1_gifs_search&rid=giphy.gif&ct=g"width=300 height=200> <br>
</p>

Seperti yang sudah disinggung sebelumnya, Arduino ini memiliki beberapa komponen yang penting di dalamnya. Ingin lihat secara detail? [Arduino UNO](uno-component.md). Nah, berikut ini adalah penjelasan dari masing-masing komponen Arduino:
1. Mikrokontroler
   
   Komponen pertama adalah mikrokontroler. Mikrokontroler adalah chip yang memungkinkan kamu memprogram Arduino dan memproses output berdasarkan input yang diberikan. Singkatnya, mikrokontroler ini adalah otak dari Arduino. Ada banyak jenis chip yang digunakan tergantung dari jenis Arduino-nya.

2. Pin
   
   Selanjutnya adalah pin. Pin ini digunakan untuk menghubungkan Arduino dengan berbagai komponen yang akan kamu gunakan. Dalam Arduino sendiri ada dua jenis pin, yakni pin analog dan pin digital.
  
- Pin digital
Pin ini dapat menerima atau mengirim sinyal digital. Digital berarti sinyal yang diterima atau dikirimkan akan bernilai 1 atau 0 alias HIGH atau LOW. Kebanyakan perangkat Arduino memiliki 14 pin input output digital.

- Pin analog
Pin analog pada arduino adalah pin yang digunakan untuk menerima input analog. Ia dapat menerima tegangan analog dari 0V sampai dengan 5V. Umumnya, setiap jenis Arduino memiliki setidaknya satu pin analog.

Setiap pin pada Arduino biasanya dapat dikonfigurasikan ke dalam dua mode, yaitu input dan output. Pada mode input, pin akan diatur untuk dapat menerima sinyal input. Sama halnya pada mode output, pin akan diatur untuk mengirimkan sinyal.

3. Konektor
   
   Komponen yang terakhir adalah konektor. Arduino sendiri memiliki dua jenis konektor yang cukup penting, yaitu power konektor dan serial konektor.

- Power konektor
Power konektor adalah konektor yang digunakan untuk menyalurkan daya untuk Arduino. Daya ini digunakan untuk menghidupkan Arduino dan juga perangkat lain yang terhubung dengannya, seperti sensor dan layar monitoring.

- Serial konektor
Serial konektor ini biasanya digunakan untuk menghubungkan Arduino dengan perangkatmu seperti komputer atau laptop. Konektor ini menggunakan port USB standar pada Arduino. Selain itu, konektor ini juga dapat digunakan sebagai power konektor. Namun, serial konektor hanya diimplementasikan pada perangkat Arduino yang lebih baru.

_@dikoding_

## 🔬 Topik Pembahasan Arduino 🔬

Untuk menggunakan repositori dengan maksimal, kalian perlu belajar programming dasar dahulu. Silahkan ikuti alur belajar berikut untuk mempelajari dasar - dasar pemograman langsung menggunakan Python

| Langkah |              Topik               |                                  Target Pembelajaran                                  |            Materi Rujukan             |
| :-----: | :------------------------------: | :-----------------------------------------------------------------------------------: | :-----------------------------------: |
|   01    | Introduksi Pemograman dan Python | Memahami apa itu membuat program dan apa peran Python dalam proses pembuatan program  |    [Materi](Basic/01_introduction)    |
|   02    |            Tipe data             |                              Memahami apa itu tipe data                               |     [Materi](Basic/02_tipe_data)      |
|   03    |             Variabel             |                               Memahami apa itu variabel                               |      [Materi](Basic/03_variable)      |
|   04    |             Operasi              | Dapat melakukan operasi sederhana menggunakan program yang ditulis menggunakan Python |      [Materi](Basic/04_operator)      |
|   05    |              String              |                                    Memahami String                                    |       [Materi](Basic/05_string)       |
|   06    |         Input dan Output         |                        Memahami cara mengambil input dari user                        |    [Materi](Basic/06_input_output)    |
|   07    |          Pengkondisian           |  Memahami salah satu dari inti dari membuat pemograman yaitu melakukan pengkondisian  | [Materi](Basic/07_logika_percabangan) |
|   08    |            Perulangan            |            Memahami inti kedua dari pemograman yaitu melakukan perulangan             |     [Materi](Basic/08_perulangan)     |
|   09    |              Fungsi              |                    Mengenal konsep fungsi dalam teknik pemograman                     |       [Materi](Basic/09_fungsi)       |
|   10    |          List dan Tuple          |                    Memahami konsep list dan tuple secara mendalam                     |     [Materi](Basic/10_list_tuple)     |
|   11    |        Manipulasi String         |                       Memahami cara memanipulasi sebuah string                        | [Materi](Basic/11_manipulasi_string)  |
|   12    |            Exception             |                         Memahami konsep exception pada python                         |     [Materi](Basic/12_exception)      |
|   13    |              Module              |                  Memahami cara mengimport sebuah module pada python                   |       [Materi](Basic/13_module)       |
|   14    |             Datetime             |                         Mengenal module datetime pada python                          |  [Materi](Basic/14_python_datetime)   |
|   15    |               Math               |                           Mengenal module math pada python                            |    [Materi](Basic/15_python_math)     |
|   16    |              kelas               |                              Mengenal kelas pada python                               |       [Materi](Basic/16_class)        |

Setelah menyelesaikan seluruh rangkaian pengenalan dasar - dasar pemograman, kalian dapat mulai untuk mempelajari topik - topik lain yang jauh lebih seru!
Untuk sekarang, mulai saja dulu dengan [Object Oriented Programming](object_oriented_programming/README.md)

## 🎓 Topik Lanjutan 🎓

Jika kalian sudah menguasai dasar - dasar pemograman beserta dengan paradigma _IoT_, kalian bisa langsung mengeksplorasi topik - topik lain yang jauh lebih menantang dan tidak kalah seru. Di repositori ini, kami telah menyiapkan beberapa topik yang mungkin kamu suka.

1.  [Arduino IoT](/iot)

2.  [The Next Future](/future)

## ⚡ Quick Access ⚡

Semua _script_ yang ada pada repositori ini, dapat diakses dengan cepat lewat link berikut:

- [Pembahasan](Arduino/README.md)
- [Algoritma](algorithm)
- [Implementasi](implementation)
  - [Blockchain](implementation/blockchain)
  - [Celular automata](implementation/celular_automata)
  - [Chiper](implementation/chiper)
  - [Compression](implementation/compression)
  - [Electro](implementation/electro)
  - [File transfer](implementation/file_transfer)
  - [Fractal](implementation/fractal)
  - [Geodesy](implementation/geodesy_programming)
  - [Physics](implementation/physics)
- [Web Programming](web_programming)
- [Implementasi Matematika](math)

## 🤩 Ayo ikut kami dan berkontribusi! 🤩

Bantuan kalian diperlukan Agar Bellshade dapat lebih jauh lagi membantu anak-anak Indonesia belajar _programming_, kita butuh tenaga kalian!

> "Dengan Bellshade, aku jadi bisa _ngoding_! Terima kasih Bellshade!"

Kami sangat senang bila kalian ingin melakukan kontribusi pada repositori **Python** ini. Tapi, sebelum itu, silahkan baca terlebih dahulu [peraturan dan pedomannya](CONTRIBUTING.md) yang telah kami siapkan. Terima kasih!

Untuk informasi lebih lanjut, mari gabung dalam komunitas [Discord Channel WPU](http://discord.gg/S4rrXQU) dan [Discord Channel Kelas Terbuka](https://discord.gg/eavqxxTU)
