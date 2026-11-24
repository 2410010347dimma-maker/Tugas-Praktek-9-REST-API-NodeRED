# Tugas Praktek 9 - REST API Node-RED untuk Sistem IoT

- **Nama:** [Dimma]
- **NPM:** [2410010347]
- **Mata Kuliah:** Internet of Things (IoT)

## Deskripsi Proyek
Sistem monitoring dan kontrol perangkat IoT berbasis MQTT, Node-RED sebagai backend REST API, dan Custom Web Dashboard (HTML/CSS/JS)[cite: 1].

## Struktur File
- `simulasi_esp32.py` — Simulator sensor suhu & kelembaban ESP32 yang mem-publish data ke broker MQTT (`localhost:1883`) pada topik `iot/sensor`[cite: 1, 2].
- `flows.json` — Konfigurasi flow Node-RED sebagai REST API backend (`GET /api/suhu`, `GET /api/history`, `POST /api/kontrol`)[cite: 3, 9].
- `dashboard.html` — Antarmuka web dashboard untuk monitoring data sensor secara real-time dan kontrol lampu via REST API[cite: 1, 9, 11].

## Hasil Uji Coba
### 1. Tampilan Web Dashboard
![Dashboard IoT](screenshot-dashboard.jpg)

### 2. Flow Node-RED
![Flow Node-RED](screenshot-nodered.jpg)