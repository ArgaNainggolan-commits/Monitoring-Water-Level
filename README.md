# Sistem Pemantauan Tinggi Permukaan Air Danau Toba Berbasis IoT (LoRa)

Sistem pemantauan lingkungan perairan *real-time* berskala luas yang dirancang untuk mengukur dan memantau fluktuasi ketinggian permukaan air Danau Toba. Proyek ini mengatasi tantangan geografis wilayah perairan yang luas dan minim jangkauan sinyal seluler standar dengan mengimplementasikan teknologi komunikasi nirkabel jarak jauh berbasis LoRa (*Long Range*).

## 🚀 Fitur Utama & Arsitektur Sistem
* **Pengukuran Sensor Real-Time:** Menggunakan sensor ketinggian air berbasis mikrokontroler untuk mengambil data akurat secara berkala.
* **Transmisi LoRa (*Long Range*):** Mengirimkan paket data sensor dari titik pemantauan di tepi/tengah perairan menuju *gateway* utama tanpa bergantung pada jaringan internet seluler komersial.
* **Embedded Data Logging:** Penyimpanan dan pemrosesan data lokal sebelum diteruskan ke *dashboard* pemantauan pusat.

## 🛠️ Stack Teknologi & Perangkat
* **Hardware & Mikrokontroler:** Arduino / Microcontroller Board, Sensor Ketinggian Air, Modul Komunikasi LoRa.
* **Bahasa Pemrograman:** C / C++ (Arduino IDE).
* **Komunikasi & Protokol:** LoRa RF Communication, SPI/I2C Protocol.
