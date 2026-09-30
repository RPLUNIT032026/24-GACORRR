<div align="center">

# 🏭GDT

### Digital Twin Gudang — Pemantauan Suhu & Asap Secara Real-Time

*Kembaran digital yang menjaga gudang tetap aman.*

![Status](https://img.shields.io/badge/Sprint-1%20(Project%20Setup)-2ea44f?style=for-the-badge)
![Mata Kuliah](https://img.shields.io/badge/Mata%20Kuliah-Rekayasa%20Perangkat%20Lunak-orange?style=for-the-badge)

</div>

---

## ✨ Tentang Proyek

**GDT** adalah aplikasi *digital twin* untuk gudang. Setiap zona di gudang (rak, ruang penyimpanan, area bongkar muat) punya **kembaran digital** di layar yang menampilkan kondisi aslinya: **suhu** dan **kadar asap**.

Kalau ada zona yang mulai panas atau berasap, kembaran digitalnya langsung berubah warna dan sistem mencatat alarm, sehingga potensi kebakaran bisa terdeteksi lebih dini.

---

## 🎯 Fitur Utama

| | Fitur | Deskripsi |
|---|---|---|
| 🌡️ | **Monitoring Suhu** | Suhu tiap zona gudang diperbarui berkala |
| 💨 | **Monitoring Asap** | Kadar asap (ppm) tiap zona dipantau terus-menerus |
| 🚦 | **Status Tiga Level** | Aman 🟢 · Waspada 🟡 · Bahaya 🔴 |
| 🚨 | **Alarm Otomatis** | Setiap kondisi bahaya tercatat lengkap dengan waktu |
---

## 🚦 Ambang Batas Status

| Status | Suhu | Kadar Asap |
|---|---|---|
| 🟢 **Aman** | < 35 °C | < 300 ppm |
| 🟡 **Waspada** | 35 – 45 °C | 300 – 600 ppm |
| 🔴 **Bahaya** | > 45 °C | > 600 ppm |

Ambang batas bisa diubah admin per zona.


Detail lengkap ada di [System Design](docs/system-design.md).

---

## 📄 Dokumen Sprint 1

| # | Dokumen | Keterangan |
|---|---|---|
| 1 | 📋 [Project Charter](docs/project-charter.md) | Latar belakang, tujuan, ruang lingkup, risiko |
| 2 | 🧮 [Perhitungan Function Point](docs/function-point.md) | Estimasi ukuran fungsionalitas aplikasi |
| 3 | 📝 [Product Backlog & Sprint 1 Backlog](docs/product-backlog.md) | User story dan target pekerjaan |
| 4 | 🧩 [System Design](docs/system-design.md) | Arsitektur, flowchart, dan ERD |
| 5 | 🎨 [Desain UI/UX](docs/ui-design.md) | Wireframe, palet warna, dan alur pengguna |

---

## 📁 Struktur Repository

```
Digital-Twin-RPL/
├── README.md
├── docs/
│   ├── project-charter.md
│   ├── function-point.md
│   ├── product-backlog.md
│   ├── system-design.md
│   └── ui-design.md
└── backend/        ← API & simulator sensor
```


## 🗓️ Roadmap

- [x] **Sprint 1** — Perencanaan, desain, dan project setup
- [ ] **Sprint 2** — API sensor dan logika status
- [ ] **Sprint 3** — Dashboard denah gudang dan grafik riwayat
- [ ] **Sprint 4** — Alarm, pengujian, dan **Product Release**

---

## 👥 Tim

| No | Nama | NIM | Akun GitHub | Fokus Sprint 1 |
|:---:|---|:---:|---|---|
| **1** | Muhammad Rizky Syaban | 240504081 | [@Iksyaban14](https://github.com/Iksyaban14) | Project Charter & Product Backlog |
| **2** | Muhammad Arby | 240504089 | [@Arby2464](https://github.com/Arby2464) | Project Setup & System Design |
| **3** | Muhammad Fazil Fayyaz | 240504084 | [@FazilFayyaz](https://github.com/FazilFayyaz) | Function Point & Desain UI/UX |
---

<div align="center">

**Universitas Samudera** · Program Studi Informatika
Mata Kuliah Rekayasa Perangkat Lunak · 2026

*Dibuat dengan ☕ dan sedikit rasa panik menjelang deadline.*

</div>
