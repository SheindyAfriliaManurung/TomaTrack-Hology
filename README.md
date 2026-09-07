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
