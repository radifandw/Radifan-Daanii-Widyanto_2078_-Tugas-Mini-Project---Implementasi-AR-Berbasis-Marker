# AR Human Anatomy - Kidney Viewer

## Identitas Mahasiswa

| | |
|---|---|
| **Nama** | Radifan Daanii Widyanto |
| **NIM** | 232410102078 |
| **Mata Kuliah** | Augmented Reality |
| **Dosen Pengampu** | Narandha Arya Ranggianto S.Kom. M.Kom. |

---

## Deskripsi Aplikasi

Aplikasi AR Human Anatomy - Kidney Viewer adalah aplikasi Augmented Reality berbasis marker yang dikembangkan menggunakan Unity dan Vuforia Engine. Aplikasi ini menampilkan model 3D organ tubuh manusia secara real-time ketika kamera diarahkan ke marker yang telah ditentukan.

Aplikasi ini memiliki dua marker berbeda:
- **Marker 1 (Kidney Anatomy)** — Menampilkan model 3D ginjal manusia lengkap dengan detail anatomi
- **Marker 2 (Human Body)** — Menampilkan model 3D tubuh manusia secara keseluruhan

Tujuan aplikasi ini adalah sebagai media pembelajaran anatomi tubuh manusia berbasis teknologi AR yang interaktif dan informatif.

---

## Teknologi yang Digunakan

- **Unity** 2022.3 LTS (Built-In Render Pipeline)
- **Vuforia Engine SDK** — sebagai framework AR berbasis marker
- **Blender** — untuk pembuatan model 3D organ tubuh

---

## Fitur Aplikasi

- Deteksi 2 marker berbeda (multi-target)
- Menampilkan model 3D ginjal di atas marker kidney anatomy
- Menampilkan model 3D tubuh manusia di atas marker human body
- Objek 3D dilengkapi material dan texture
- Rotasi otomatis pada objek 3D

---

## Cara Menjalankan Aplikasi

1. Clone repository ini
2. Buka project menggunakan **Unity 2022.3 LTS**
3. Pastikan **Vuforia Engine SDK** sudah terinstall
4. Masukkan License Key Vuforia di AR Camera configuration
5. Print atau tampilkan marker di layar
6. Tekan **Play** di Unity Editor
7. Arahkan webcam ke marker — objek 3D akan muncul

---

## Marker

Gambar marker tersedia di folder `/Markers`:
- `kidney_marker.png` — Marker anatomi ginjal
- `human_marker.png` — Marker tubuh manusia

---

## Video Demo

Tonton video presentasi dan demo aplikasi di YouTube:

🎥 [https://youtu.be/W9fX50LVYzs](https://youtu.be/W9fX50LVYzs)

---

## Struktur Project

```
AnatomyAR/
├── Assets/
│   ├── Models/         # Model 3D ginjal dan tubuh manusia
│   ├── Materials/      # Material dan texture objek
│   ├── Scenes/         # Scene utama aplikasi
│   └── StreamingAssets/ # Database marker Vuforia
│   └── Teksture/ # Mengatasi Bug teksture 
├── Markers/
│   ├── kidney_marker.png
│   └── human_marker.png
├── ProjectSettings/
└── README.md
```

## Gambar Marker

<img width="960" height="720" alt="Blausen_0592_KidneyAnatomy_01" src="https://github.com/user-attachments/assets/548db17a-4eac-485f-8ad5-8da61ee3fca7" />
