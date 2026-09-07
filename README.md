# TomaTrack

## Smart Tomato Plant Monitoring System

TomaTrack adalah sistem pemantauan tanaman tomat berbasis **Internet of Things (IoT)** dan **Computer Vision** yang dirancang untuk membantu memantau kondisi lingkungan tanaman serta mengidentifikasi kondisi daun tomat.

Sistem mengintegrasikan ESP32 sebagai perangkat monitoring, ESP32-CAM sebagai perangkat akuisisi citra, MQTT sebagai protokol komunikasi, AI Server untuk proses klasifikasi citra, serta dashboard web sebagai antarmuka monitoring.

## Fitur Utama

- Plant Monitoring — monitoring suhu, kelembapan udara, dan kelembapan media tanam secara real-time.
- Analisis Kesehatan — identifikasi kondisi atau penyakit daun menggunakan model MobileNetV2.
- History — menyimpan riwayat data sensor dan hasil prediksi.
- Control Panel — kontrol dan informasi perangkat.
- Rekomendasi — memberikan rekomendasi berdasarkan kondisi tanaman.

### Teknologi

- ESP32 DevKit
- ESP32-CAM
- DHT22
- Soil Moisture Sensor
- OLED Display
- MQTT & HiveMQ
- Python & Flask
- TensorFlow / Keras
- MobileNetV2
- OpenCV
- PlantVillage Dataset

## Arsitektur Sistem

Secara umum, sistem TomaTrack terdiri dari beberapa bagian:
<img width="354" height="407" alt="Screenshot 2026-09-07 042706" src="https://github.com/user-attachments/assets/dbfc09c0-facf-4e99-bcd0-5f1815233514" />

## Skematik Alat

Skematik alat menunjukkan hubungan antar komponen hardware yang digunakan pada sistem TomaTrack.
<img width="317" height="244" alt="Screenshot 2026-09-06 214219" src="https://github.com/user-attachments/assets/5a1827e7-3820-436a-a0d0-2f04d6a6e226" />


## Computer Vision

Model MobileNetV2 digunakan untuk mengklasifikasikan daun tomat ke dalam 10 kelas, yaitu:

Bacterial Spot
Early Blight
Late Blight
Leaf Mold
Septoria Leaf Spot
Spider Mites (Two-spotted)
Target Spot
Yellow Leaf Curl Virus
Mosaic Virus
Healthy

## Hasil Pengujian

Model diuji menggunakan 2.724 citra dan berhasil mengklasifikasikan 2.493 citra dengan benar.

Accuracy: 91,52%
Macro Precision: 90,43%
Macro Recall: 90,23%
Macro F1-Score: 89,51%
