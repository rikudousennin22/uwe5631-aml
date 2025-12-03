# UWE5621-AML (Improved UWE5621 Driver for Amlogic)

Project ini merupakan hasil pengembangan dan perbaikan dari repository asli:
- https://github.com/simonchen007/uwe5621-aml  
- https://github.com/sib0ndt/unisoc_uwe5621
- https://github.com/CoreELEC/uwe5631-aml

Tujuan utama project ini adalah meningkatkan stabilitas dan fungsi driver WiFi Unisoc UWE5621/UWE5631 pada perangkat berbasis Amlogic, terutama untuk penggunaan di OpenWrt dan kernel Linux versi terbaru.

---
![uwe5631 preview](https://raw.githubusercontent.com/rikudousennin22/uwe5631-aml/main/%7BC205B622-EE87-4607-B98A-4BA2827054F2%7D.png)

## ✨ Perubahan dan Perbaikan

### ✔️ Perbaikan Client WiFi Tidak Terdeteksi
Bug yang menyebabkan client tidak muncul pada daftar station (iw/hostapd_cli) telah diperbaiki.

### ✔️ TX/RX Per-Client Sudah Berfungsi
Statistik transmit dan receive kini bisa muncul dan terlapor dengan benar untuk tiap device.

### ✔️ Signal / Noise Sudah Muncul (Belum Stabil)
Nilai Signal dan Noise sudah bisa dibaca, namun masih belum stabil dan membutuhkan tuning lebih lanjut.

---

## 🎯 Tujuan Pengembangan

- Meningkatkan stabilitas driver UWE5621/UWE5631.
- Menghilangkan masalah throughput turun ketika banyak client tersambung.
- Memperbaiki kompatibilitas dengan nl80211, iw, dan hostapd.
- Optimasi gain RF, power management, dan statistik WiFi.

---

## 📌 Status Saat Ini

| Fitur | Status |
|-------|--------|
| Client detection | ✔️ Sudah diperbaiki |
| TX/RX per-client | ✔️ Sudah jalan |
| Signal/Noise | ⚠️ Belum stabil |
| Multi-client throughput | ⚠️ Perlu tuning |
| Integrasi OpenWrt | ⏳ Progres bertahap |

---

## 📁 Sumber Asli

Project ini dikembangkan dari:
https://github.com/simonchen007/uwe5621-aml

Terima kasih kepada pengembang asli atas manusianya.

---

## 🤝 Kontribusi

Kontribusi sangat diterima untuk:
- Tuning RF & Noise
- Debug SDIO
- Porting ke kernel baru
- Perbaikan compatibility hostapd/wpa_supplicant

---

## 📄 Lisensi

Mengikuti lisensi dari project asli (GPL).




