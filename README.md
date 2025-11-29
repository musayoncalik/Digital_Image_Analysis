# 📷 Dijital Görüntü Çözümleme (Digital Image Analysis)

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange?style=for-the-badge&logo=jupyter)
![Status](https://img.shields.io/badge/Status-Active%20%2F%20Updating-brightgreen)

Bu repo, **Dijital Görüntü Çözümleme** dersi kapsamında gerçekleştirilen haftalık çalışmaları, laboratuvar uygulamalarını ve görüntü işleme projelerini içermektedir.

> 📢 **Not:** Bu repo, ders müfredatına paralel olarak dönem boyunca **güncellenmeye ve yeni içerikler eklenmeye** devam edecektir.

---

## 📖 Ders Bilgileri

| Konu | Açıklama |
|------|----------|
| **Kapsam** | Dijital görüntülerin bilgisayar ortamında elde edilmesi, işlenmesi, analiz edilmesi ve anlamlandırılması. |
| **Amaç** | Görüntü işleme tekniklerinin teorik temellerini öğrenmek ve Python + OpenCV ile uygulamak. |
| **Hedef** | Görüntü matrisleri, iyileştirme, nesne tespiti, yüz tanıma ve öznitelik çıkarımı uygulamaları geliştirmek. |

---

## 🛠 Kullanılan Teknolojiler

![Python](https://img.shields.io/badge/Python-3.x-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-green)
![NumPy](https://img.shields.io/badge/NumPy-yellow)
![Matplotlib](https://img.shields.io/badge/Matplotlib-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-purple)

---

## 📂 Klasör Yapısı


Digital_Image_Analysis/
│
├── assets/        # README ve proje ekran görüntüleri
├── week/          # Giriş, Kurulum ve Python Temelleri
├── week_2/        # Temel Görüntü İşlemleri (Basic Image Operations)
├── week_3/        # Renkli Görüntü Oluşturma (Color Image Creation)
├── week_4/        # Temel Geometrik Dönüşümler
├── week_5/        # Eşikleme (Thresholding) Teknikleri
├── week_6/        # Morfolojik İşlemler (Morphological Processing)
├── week_7/        # Kontur Tespiti (Contour Detection)
├── week_8/        # Bulanıklaştırma ve Filtreleme
├── week_10/       # İleri Seviye Analiz ve Öznitelik Çıkarımı
├── week_11/       # Yüz Tespiti (Face Detection - Haar Cascade)
├── ...            # Yeni haftalar eklendikçe güncellenecektir
└── .gitignore     # Git tarafından yok sayılacak dosyalar

<pre>
📝 Çalışma Konuları ve Detaylar
1️⃣ Basic Image Operations
- Görüntü okuma, gösterme ve kaydetme
- Piksel manipülasyonu ve ROI (Region of Interest)

2️⃣ Color Image Creation and Manipulation
- Renk uzayları dönüşümleri: RGB, BGR, HSV, GRAY
- Renk kanallarını ayırma ve birleştirme

3️⃣ Basic Geometric Image Transformations
- Ölçekleme (Scaling), Döndürme (Rotation), Öteleme (Translation)
- Perspektif ve afin dönüşümler

4️⃣ Thresholding and Intensity Transformations
- Simple Thresholding, Adaptive Thresholding, Otsu Binarization
- Histogram eşitleme ile kontrast artırma

5️⃣ Morphological Image Processing
- Gürültü temizleme ve yapısal analiz
- Erozyon, Genişletme, Açma, Kapama

6️⃣ Contour Detection and Visualization
-Nesne sınırlarını bulma algoritmaları
- Kontur özelliklerini hesaplama (Alan, Çevre, Merkez)

7️⃣ Face Detection Using Haar Cascade Classifier
- Önceden eğitilmiş XML modelleri (haarcascade_frontalface_default)
- Gerçek zamanlı veya statik görüntülerde yüz tespiti ve işaretleme

📸 Örnek Görüntüler
<div align="center">
Morfolojik İşlem
<img src="assets/morphological_example.png" width="400"/>

Kontur Tespiti (Contour Detection)
<img src="assets/contour_example.png" width="400"/>

Yüz Tespiti (Face Detection)
<img src="assets/face_detection_example.png" width="400"/>

</div>
  
⚙️ Kurulum ve Çalıştırma
1️⃣ Repoyu Klonlayın

git clone https://github.com/kullaniciadi/Digital_Image_Analysis.git
cd Digital_Image_Analysis

  
2️⃣ Sanal Ortam Oluşturun (Opsiyonel ama önerilir)
python -m venv venv
# Windows
venv\Scripts\activate
  
# Mac/Linux
source venv/bin/activate

  
3️⃣ Gerekli Kütüphaneleri Yükleyin

pip install opencv-python numpy matplotlib jupyter

  
4️⃣ Projeyi Çalıştırın

jupyter notebook
Tarayıcı üzerinden ilgili haftanın .ipynb dosyasını açabilirsiniz.  </pre> 
