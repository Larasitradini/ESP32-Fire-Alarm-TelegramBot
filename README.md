# ESP32-Fire-Alarm-TelegramBot
Project tugas kuliah: deteksi api dengan ESP32 + notifikasi Telegram
# ESP32 Fire Alarm with Telegram Bot 🚨

Project ini dibuat menggunakan **ESP32** di platform **Wokwi** untuk tugas kuliah Teknik Telekomunikasi.  
Fungsinya adalah mendeteksi kondisi bahaya (asap/api) dengan sensor, lalu mengirimkan **notifikasi ke Telegram Bot**.  
Buzzer akan berbunyi jika bahaya terdeteksi.

## 🔧 Hardware
- ESP32
- Sensor Api
- Buzzer

## 📚 Library
- WiFi.h
- WiFiClientSecure.h
- UniversalTelegramBot.h

## 🚀 Cara Menjalankan
1. Buka file `sketch.ino` di Arduino IDE.
2. Masukkan SSID WiFi dan token Telegram pada kode.
3. Upload program ke ESP32.
4. Jalankan simulasi di [Wokwi](https://wokwi.com).

## 📷 Screenshot
![Diagram Rangkaian](diagram.png)

## 🔗 Link Wokwi Project
👉 [Klik di sini untuk mencoba project di Wokwi](https://wokwi.com/projects/431819788115018753)
