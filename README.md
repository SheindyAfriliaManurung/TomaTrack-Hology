# TomaTrack

## Smart Tomato Plant Monitoring System

TomaTrack adalah sistem pemantauan tanaman tomat berbasis **Internet of Things (IoT)** dan **Computer Vision** yang dirancang untuk membantu memantau kondisi lingkungan tanaman serta mengidentifikasi kondisi daun tomat.

Sistem mengintegrasikan ESP32 sebagai perangkat monitoring, ESP32-CAM sebagai perangkat akuisisi citra, MQTT sebagai protokol komunikasi, AI Server untuk proses klasifikasi citra, serta dashboard web sebagai antarmuka monitoring.

---

## Fitur Utama

- Monitoring suhu udara
- Monitoring kelembapan udara
- Monitoring kelembapan media tanam
- Akuisisi citra daun menggunakan ESP32-CAM
- Klasifikasi kondisi daun menggunakan Computer Vision
- Prediksi kondisi daun beserta nilai confidence
- Komunikasi data menggunakan MQTT
- Dashboard monitoring tanaman
- Dashboard analisis kesehatan tanaman
- Riwayat data monitoring dan hasil prediksi
- Control Panel
- Indikator peringatan menggunakan buzzer

---

## Arsitektur Sistem

Secara umum, sistem TomaTrack terdiri dari beberapa bagian:
<img width="354" height="407" alt="Screenshot 2026-09-07 042706" src="https://github.com/user-attachments/assets/dbfc09c0-facf-4e99-bcd0-5f1815233514" />
