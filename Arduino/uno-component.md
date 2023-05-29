## 🔧 Komponen Pada Arduino UNO 🔧
<p align="center">
  <img src="https://1.bp.blogspot.com/-T0DO9wtfnks/XqLXHspqK6I/AAAAAAAADjQ/jH78E6LV3JQZtrrFJBlP-Vx46PIUOrnYwCNcBGAsYHQ/s640/gambar-arduino-beserta-penjelasannya.jpg" width=600 height=400> <br>
</p>

1. Power USB, fungsi dari power usb pada modul Arduino adalah sebagai berikut:

- Media pemberi tegangan listrik ke Arduino
- Media tempat memasukkan program dari komputer ke Arduino
- Sebagai media untuk komunikasi serial antara komputer dan Arduino R3 maupun sebaliknya.

2. Crystal Oscillator, fungsi crystal oscillator adalah sebagai jantung Arduino yang membuat dan mengirimkan detak ke mikrokontroler agar beroperasi setiap detaknya.

3. Voltage Regulator, berfungsi menstabilkan tegangan listrik yang masuk ke Arduino.

4. Power Jack, fungsi dari power jack pada modul Arduino adalah sebagai media pemberi tegangan listrik ke Arduino apabila tak ingin menggunakan Power USB.

5. Pin Reset, berfungsi untuk mereset Arduino agar program dimulai dari awal. Cara penggunannya yaitu dengan menghubungkan pin reset ini langsung ke ground.

6. Pin Tegangan 3,3 Volt, berfungsi sebagai pin positif untuk komponen yang menggunakan tegangan 3,3 volt.

7. Pin Tegangan 5 Volt, berfungsi sebagai pin positif untuk komponen yang menggunakan tegangan 5 volt. Pin 5 volt sering juga disebut pin VCC.

8. Pin Ground (GND), fungsi pin GND adalah sebagai pin negatif pada tiap komponen yang dihubungkan ke Arduino.

9. Pin Penambah Tegangan (VIN), berfungsi sebagai media pemasok listrik tambahan dari luar sebesar 5 volt bila tak ingin menggunakan Power USB atau Power Jack.

10. Pin Analog, berfungsi membaca tegangan dan sinyal analog dari berbagai jenis sensor untuk diubah ke nilai digital.

11. Main Microcontroller, berfungsi sebagai otak yang mengatur pin-pin pada Arduino.

12. Tombol Reset, komponen pendukung Arduino yang berfungsi untuk mengulang program dari awal dengan cara menekan tombol.

13. Pin ICSP (In-Circuit Serial Programming), berfungsi untuk memprogram mikrokontroler seperti Atmega328 melalui jalur USB Atmega16U2.

14. Lampu Indikator Power, berfungsi sebagai indikator bahwa Arduino sudah mendapatkan suplai tegangan listrik yang baik.

15. Lampu TX (transmit), berfungsi sebagai penanda bahwa sedang terjadi pengiriman data dalam komunikasi serial.

16. Lampu RX (receive), berfungsi sebagai penanda bahwa sedang terjadi penerimaan data dalam komunikasi serial.

17. Pin Input/Output Digital, berfungsi untuk membaca nilai logika 1 dan 0 atau mengendalikan komponen output lain seperti LED, relay, atau sejenisnya. Pin ini termasuk paling banyak digunakan saat membuat rangkaian.
Untuk pin yang berlambang “~” artinya dapat digunakan untuk membangkitkan PWM (Pulse With Modulation) yang fungsinya bisa mengatur tegangan output. Biasanya digunakan untuk mengatur kecepatan kipas atau mengatur terangnya cahaya lampu.

18. Pin AREF (Analog Reference), fungsi pin Arduino Uno yang satu ini untuk mengatur tegangan referensi eksternal yang biasanya berada di kisaran 0 sampai 5 volt.

19. Pin SDA (Serial Data), berfungsi untuk menghantarkan data dari modul I2C atau yang sejenisnya.

20. Pin SCL (Serial Clock), berfungsi untuk menghantarkan sinyal waktu (clock) dari modul I2C ke Arduino.
