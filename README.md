# 📷 Dijital Görüntü Çözümleme (Digital Image Analysis)

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange?style=for-the-badge&logo=jupyter)
![Status](https://img.shields.io/badge/Status-Active%20%2F%20Updating-brightgreen)

Bu repo, **Dijital Görüntü Çözümleme** dersi kapsamında gerçekleştirilen haftalık çalışmaları, laboratuvar uygulamalarını ve görüntü işleme projelerini içermektedir.

> 📢 **Not:** Bu repo, ders müfredatına paralel olarak dönem boyunca **güncellenmeye ve yeni içerikler eklenmeye** devam edecektir.

---

## 📖 Ders Bilgileri

### 📍 Konusu
Dijital görüntülerin bilgisayar ortamında elde edilmesi, işlenmesi, analiz edilmesi ve anlamlandırılması süreçleri.

### 🚀 Amacı
Görüntü işleme tekniklerinin teorik temellerini kavramak ve bu teknikleri **Python** ve **OpenCV** kütüphanesi kullanarak gerçek dünya problemlerine uygulamaktır.

### 🎯 Hedefi
* Görüntü matrisleri üzerinde hakimiyet kurmak.
* Görüntü iyileştirme, gürültü giderme ve netleştirme işlemlerini yapabilmek.
* Nesne tespiti, yüz tanıma ve öznitelik çıkarımı gibi bilgisayarlı görü (Computer Vision) uygulamaları geliştirmek.

---

## 🛠 Kullanılan Teknolojiler ve Kütüphaneler

Projelerde aşağıdaki teknoloji yığını kullanılmıştır:

* **Dil:** Python 3.x
* **Görüntü İşleme:** OpenCV (`cv2`)
* **Matematiksel İşlemler:** NumPy
* **Veri Görselleştirme:** Matplotlib
* **Geliştirme Ortamı:** Jupyter Notebook / Visual Studio Code

---

## 📂 İçerik ve Klasör Yapısı

Repo içerisindeki çalışmalar haftalık ilerlemeye göre düzenlenmiştir. Ders ilerledikçe yeni haftalar eklenecektir.

```text
Digital_Image_Analysis/
│
├── assets/        # README ekran görüntüleri
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
├── ...            # (Yeni haftalar eklendikçe güncellenecektir)
└── .gitignore     # Git tarafından yok sayılacak dosyalar
📝 Çalışma Konuları ve Detaylar
Bu derste işlenen ve kodlanan ana başlıklar şunlardır:

1. Basic Image Operations
TR: Temel Görüntü İşlemleri

Görüntü okuma, gösterme ve kaydetme.

Piksel manipülasyonu ve ROI (İlgi Alanı/Region of Interest) işlemleri.

2. Color Image Creation and Manipulation
TR: Renkli Görüntü Oluşturma ve Manipülasyon

Renk uzayları arası dönüşümler (RGB, BGR, HSV, GRAY).

Renk kanallarını ayırma ve birleştirme işlemleri.

3. Basic Geometric Image Transformations
TR: Temel Geometrik Görüntü İşlemleri

Görüntü üzerinde Ölçekleme (Scaling), Döndürme (Rotation) ve Öteleme (Translation).

Perspektif ve afin dönüşümleri.

4. Thresholding and Intensity Transformations
TR: Eşikleme ve Piksel Yoğunluğu Dönüşümleri

Basit eşikleme (Simple Thresholding) yöntemleri.

Adaptive Thresholding ve Otsu Binarization teknikleri.

Histogram eşitleme ile kontrast artırma.

5. Morphological Image Processing
TR: Morfolojik Görüntü İşleme

Gürültü temizleme ve yapısal analiz işlemleri.

Erozyon (Erosion), Genişletme (Dilation), Açma (Opening) ve Kapama (Closing).

6. Contour Detection and Visualization
TR: Kontur Tespiti ve Görselleştirme

Görüntüdeki nesnelerin sınırlarını bulma algoritmaları.

Kontur özelliklerini hesaplama (Alan, Çevre, Merkez Noktası).

7. Face Detection Using Haar Cascade Classifier
TR: Haar Cascade Sınıflandırıcı ile Yüz Tespiti

Önceden eğitilmiş XML modelleri (haarcascade_frontalface_default) kullanımı.

Gerçek zamanlı (webcam) veya statik görüntülerde yüz tespiti ve işaretleme.

📸 Ekran Görüntüleri (Screenshots)
Ders kapsamında yapılan uygulamalardan elde edilen çıktılar:

🔹 Morfolojik İşlem Örneği
🔹 Kontur Tespiti (Contour Detection)
🔹 Yüz Tespiti (Face Detection)
⚙️ Kurulum ve Çalıştırma
Bu projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

Repoyu Klonlayın:

Bash

git clone [https://github.com/kullaniciadi/Digital_Image_Analysis.git](https://github.com/kullaniciadi/Digital_Image_Analysis.git)
cd Digital_Image_Analysis
Sanal Ortam Oluşturun (Opsiyonel ama önerilir):

Bash

python -m venv venv
# Windows için:
venv\Scripts\activate
# Mac/Linux için:
source venv/bin/activate
Gerekli Kütüphaneleri Yükleyin:

Bash

pip install opencv-python numpy matplotlib jupyter
Projeyi Çalıştırın: Jupyter Notebook kullanıyorsanız:

Bash

jupyter notebook
Komutunu çalıştırıp tarayıcı üzerinden ilgili haftanın .ipynb dosyasını açabilirsiniz.
