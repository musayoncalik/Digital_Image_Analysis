# 📷 Dijital Görüntü Çözümleme (Digital Image Analysis)

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange?style=for-the-badge&logo=jupyter)
![Status](https://img.shields.io/badge/Status-Active%20%2F%20Updating-brightgreen)

Bu repo, **Dijital Görüntü Çözümleme** dersi kapsamında gerçekleştirilen haftalık çalışmaları, laboratuvar uygulamalarını ve görüntü işleme projelerini içermektedir.

> 📢 **Not:** Bu repo, ders müfredatına paralel olarak dönem boyunca **güncellenmeye ve yeni içerikler eklenmeye** devam edecektir.

---

## 📖 Ders Bilgileri

| Bilgi | Detay |
| :--- | :--- |
| **Ders Adı** | Dijital Görüntü Çözümleme |
| **📍 Konusu** | Dijital görüntülerin bilgisayar ortamında elde edilmesi, işlenmesi, analiz edilmesi ve anlamlandırılması süreçleri. |
| **🛠Platform** | Python, OpenCV, NumPy, Matplotlib |
| **🚀 Amacı** | Görüntü işleme tekniklerinin teorik temellerini kavramak ve gerçek dünya problemlerine uygulamaktır. |
| **🎯 Hedefi** | Görüntü matrislerine hakimiyet; görüntü iyileştirme, gürültü giderme, netleştirme işlemleri ve nesne/yüz tespiti gibi bilgisayarlı görü uygulamaları geliştirmek. |
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
├── week/          # Eşikleme ve Piksel Yoğunluğu Dönüşümleri
├── week_2/        # Temel Görüntü İşlemleri (Basic Image Operations)
├── week_3/        # BASIC GEOMETRIC IMAGE TRANSFORMATIONS (Temel Geometrik Görüntü İşlemleri)
├── week_4/        # MORFOLOJICAL IMAGE PROCESSING (MORFOLOJİK GÖRÜNTÜ İŞLEME)
├── week_5/        # COLOR IMAGE CREATION AND MANIPULATION (RENKLİ GÖRÜNTÜ OLUŞTURMA VE MANİPÜLASYON) 
├── week_6/        # Kontur Tespiti ve Görselleştirme, RENKLİ GÖRÜNTÜ İŞLEME, MASKELEME VE MANİPÜLASYON
├── week_7/        # Görüntü İşleme ve Kontur Analizi, Siyah Kenarlı Görüntülerde Otomatik Kırpma, Haar Cascade Sınıflandırıcı ile Yüz Tespiti
├── week_8/        # OpenCV Kullanarak Plaka Tespiti
├── week_11/       # İleri Seviye Analiz ve Öznitelik Çıkarımı
├── ...            # (Yeni haftalar eklendikçe güncellenecektir)
├── requirements.txt   # Gerekli Python kütüphaneleri
├── README.md          # Proje dokümantasyonu ve açıklamalar
└── .gitignore     # Git tarafından yok sayılacak dosyalar

```


---

## 📝 Çalışma Konuları ve Detaylar

### 1️⃣ Basic Image Operations
- Görüntü okuma, gösterme ve kaydetme  
- Piksel manipülasyonu ve ROI (Region of Interest)

### 2️⃣ Color Image Creation and Manipulation
- Renk uzayları dönüşümleri: RGB, BGR, HSV, GRAY  
- Renk kanallarını ayırma ve birleştirme

### 3️⃣ Basic Geometric Image Transformations
- Ölçekleme (Scaling), Döndürme (Rotation), Öteleme (Translation)  
- Perspektif ve afin dönüşümler

### 4️⃣ Thresholding and Intensity Transformations
- Simple Thresholding, Adaptive Thresholding, Otsu Binarization  
- Histogram eşitleme ile kontrast artırma

### 5️⃣ Morphological Image Processing
- Gürültü temizleme ve yapısal analiz  
- Erozyon, Genişletme, Açma, Kapama

### 6️⃣ Contour Detection and Visualization
- Nesne sınırlarını bulma algoritmaları  
- Kontur özelliklerini hesaplama (Alan, Çevre, Merkez)

### 7️⃣ Face Detection Using Haar Cascade Classifier
- Önceden eğitilmiş XML modelleri (haarcascade_frontalface_default)  
- Gerçek zamanlı veya statik görüntülerde yüz tespiti ve işaretleme

---

## 📸 Örnek Görüntüler

<div align="center">

### 1. İlgi Alanı (ROI) ve Kırpma İşlemi
Görüntü üzerinde belirli bir bölgenin (Region of Interest) seçilmesi ve kırpılması.

<img width="800" alt="ROI ve Kırpma" src="<img width="1236" height="481" alt="image" src="https://github.com/user-attachments/assets/b1e5a5ae-dc6a-4676-92b6-19c34d9b75a1" />
">
<br><br>

### 2. Renkli Görüntü Oluşturma
NumPy dizileri ve matris işlemleri kullanılarak sıfırdan renkli bir görüntü (Almanya bayrağı) oluşturulması.

<img width="600" alt="Bayrak Oluşturma" src="<img width="879" height="526" alt="image" src="https://github.com/user-attachments/assets/cd0ac03f-b950-4ec7-a9c6-e123aaf47e59" />
">
<br><br>

### 3. Geometrik Dönüşümler
Görüntünün dikey ve yatay eksende aynalanması (flipping) ve döndürülmesi.

<img width="800" alt="Geometrik Dönüşüm" src="<img width="1126" height="734" alt="image" src="https://github.com/user-attachments/assets/705c12d0-8a2e-4fca-9c8d-daf743575f69" />
">
<br><br>

### 4. Morfolojik İşlemler (Gradyan)
Orijinal görüntü üzerinde erozyon ve genişletme farklarının alınarak şekil sınırlarının (Gradyan) belirginleştirilmesi.

<img width="800" alt="Morfolojik İşlemler" src="<img width="1359" height="711" alt="image" src="https://github.com/user-attachments/assets/ddb04972-8753-4915-8574-34bb453da647" />
">
<br><br>

### 5. Kontur Tespiti (Contour Detection)
Görüntüdeki nesnenin sınırlarının tespit edilmesi ve yeşil kontur çizgisi ile çizdirilmesi.

<img width="500" alt="Kontur Tespiti" src="<img width="636" height="681" alt="image" src="https://github.com/user-attachments/assets/1e4a30e4-2852-4629-82df-11bcd73aefd0" />
">
<br><br>

### 6. Yüz Tespiti (Face Detection)
Haar Cascade sınıflandırıcısı kullanılarak kalabalık bir fotoğrafta (Futbol Takımı) çoklu yüz tespiti.

<img width="800" alt="Yüz Tespiti" src="<img width="1378" height="444" alt="image" src="https://github.com/user-attachments/assets/529417c8-fea9-4b45-927b-480b450410cf" />
">

### 7. RGB Renk Uzayı ve Temel Kanallar (RGB Color Space)
Dijital görüntü işlemede temel yapı taşı olan RGB renk modelinin analizi. Saf renk kodları (Kırmızı, Yeşil, Mavi) ve bu kanalların birleşimiyle oluşan beyaz rengin piksel değerleri (Örn: `255, 0, 0`) kullanılarak oluşturulması.

<img width="800" alt="RGB Renk Uzayı ve Kanallar" src="<img width="1370" height="393" alt="image" src="https://github.com/user-attachments/assets/9301247c-0535-4908-9ccb-80a7d55a50c6" />
">

</div>

---

## ⚙️ Kurulum ve Çalıştırma

## ⚙️ Kurulum ve Çalıştırma

Bu projeyi yerel bilgisayarınızda çalıştırmak ve geliştirmek için aşağıdaki adımları sırasıyla takip edin.

### 1️⃣ Projeyi Klonlayın
Öncelikle terminal veya komut istemcisini (CMD) açın ve repoyu bilgisayarınıza indirin:

```

bash
git clone [https://github.com/kullaniciadi/Digital_Image_Analysis.git](https://github.com/kullaniciadi/Digital_Image_Analysis.git)
cd Digital_Image_Analysis

2️⃣ Sanal Ortam Oluşturun (Önerilen)
Kütüphane çakışmalarını önlemek için sanal bir ortam (virtual environment) oluşturmanız tavsiye edilir.

Bash
# Sanal ortamı oluşturma
python -m venv venv

# Sanal ortamı aktif etme:
# ---------------------------
# Windows için:
.\venv\Scripts\activate

# MacOS / Linux için:
source venv/bin/activate


3️⃣ Gerekli Kütüphaneleri Yükleyin
Projenin ihtiyaç duyduğu tüm kütüphaneleri (OpenCV, NumPy, Matplotlib vb.) tek komutla yüklemek için proje dizininde şu komutu çalıştırın:

```bash
pip install -r requirements.txt


VEYA tek tek yükleyin.
Bash
pip install opencv-python numpy matplotlib jupyter


4️⃣ Projeyi Çalıştırın
Kurulum tamamlandıktan sonra Jupyter Notebook arayüzünü başlatın:

Bash
jupyter notebook


Bu komutu yazdıktan sonra tarayıcınızda bir sayfa açılacaktır. Buradan week_X klasörlerine gidip ilgili .ipynb dosyasını seçerek kodları çalıştırabilirsiniz.
