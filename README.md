# 🚘 ScanPlakAi_YoloV12

> **Plaka Tanıma Sistemi** – YOLOv12 ile eğitilmiş, gerçek zamanlı çalışan plaka tespit modeli  
> Kamera görüntüsü üzerinden plakaları tespit eder ve sınıflandırır. FastAPI ile entegre backend desteği mevcuttur.

![License Plate Detection](https://img.shields.io/badge/Plaka%20Tanıma-YOLOv12-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Durum-Aktif-brightgreen?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.10+-yellow?style=for-the-badge)
![FastAPI](https://img.shields.io/badge/Backend-FastAPI-lightgrey?style=for-the-badge)
![Flutter](https://img.shields.io/badge/Frontend-Flutter-blue?style=for-the-badge)

---

## 📸 Hakkında

**ScanPlakAi_YoloV12**, Türkiye plakalarını tespit etmek üzere eğitilmiş, YOLOv12 tabanlı bir gerçek zamanlı nesne tanıma sistemidir.  
Mobil ve web uygulamalarla kolayca entegre edilebilecek yapıda geliştirilmiştir.

### 🎯 Özellikler

- ✅ YOLOv12 ile yüksek doğrulukta plaka tespiti
- ✅ FastAPI ile RESTful API
- ✅ Kamera veya video dosyasından canlı tespit
- ✅ Kolay eğitim ve test altyapısı
- ✅ Flutter ile mobil uygulama desteği (isteğe bağlı)

---

## 🖼️ Örnek Ekran Görüntüsü

<p align="center">
  <img src="https://www.filizguvenlik.com.tr/wp-content/uploads/2019/04/qs1jbiGDabt7IVE98EZg.jpg" width="600" alt="Plaka Tespit Örneği">
</p>

---

## 🚀 Kurulum

### 1. Ortamı Hazırla

```bash
git clone https://github.com/kullanici_adin/ScanPlakAi_YoloV12.git
cd ScanPlakAi_YoloV12
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
