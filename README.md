# 📚 Tire ŞAİK Anadolu Lisesi - Kütüphane Yönetim Sistemi

Bu proje, **Tire Şehit Albay İbrahim Karaoğlanoğlu (ŞAİK) Anadolu Lisesi** kütüphanesinin dijitalleşmesi ve kitap takip süreçlerinin hızlandırılması amacıyla geliştirilmiş, kapsamlı bir kütüphane yönetim yazılımıdır.

Okulumdaki kitap ödünç alma ve iade süreçlerini modernize etmek ve kağıt israfını önlemek amacıyla bir 10. sınıf öğrencisi olarak bu projeyi hayata geçirdim.

## ✨ Özellikler

* **🛡️ Çift Giriş Paneli:** Öğretmenler (Yönetici) ve Öğrenciler için özelleştirilmiş, şifre korumalı erişim ekranları.
* **📷 Barkod Entegrasyonu:** `pyzbar` ve `OpenCV` kullanarak kitap barkodlarını kamera ile tarama ve saniyeler içinde işlem yapma.
* **📇 Barkod Oluşturma:** Sisteme yeni eklenen kitaplar için otomatik barkod üretme ve çıktı alma desteği.
* **📊 Veritabanı Yönetimi:** SQLite ile verilerin yerel ve güvenli bir şekilde saklanması.
* **📂 Excel & CSV Entegrasyonu:** Öğrenci listelerini Excel'den toplu aktarma veya mevcut verileri rapor olarak dışarı aktarma.
* **🎨 Modern Arayüz:** `CustomTkinter` kütüphanesi ile geliştirilmiş, karanlık mod destekli ve kullanıcı dostu tasarım.
* **📈 Gelişmiş Takip:** En çok kitap okuyan öğrenciler, popüler kitaplar ve teslim süresi yaklaşan kitapların otomatik takibi.

## 🛠️ Kullanılan Teknolojiler

Proje tamamen **Python** dili kullanılarak geliştirilmiştir:

* **GUI (Arayüz):** `CustomTkinter`, `Tkinter`
* **Veritabanı:** `sqlite3`
* **Görüntü İşleme:** `OpenCV (cv2)`, `pyzbar`
* **Veri Yönetimi:** `openpyxl` (Excel), `csv`
* **Görselleştirme:** `Pillow (PIL)`
* **Barkod:** `python-barcode`

## 🚀 Kurulum ve Çalıştırma

Projeyi kendi bilgisayarınızda çalıştırmak için:

1.  **Depoyu Klonlayın:**
    ```bash
    git clone [https://github.com/kullanici-adin/tire-saik-kutuphane.git](https://github.com/kullanici-adin/tire-saik-kutuphane.git)
    cd tire-saik-kutuphane
    ```

2.  **Gerekli Kütüphaneleri Yükleyin:**
    ```bash
    pip install customtkinter opencv-python pyzbar pillow openpyxl python-barcode
    ```

3.  **Uygulamayı Başlatın:**
    ```bash
    python library_app.py
    ```

> **Önemli Not:** Barkod okuma fonksiyonu için bilgisayarınızda aktif bir kamera bulunmalıdır. macOS kullanıcıları `brew install zbar` komutu ile ek bağımlılığı kurmalıdır.

## 📸 Ekran Görüntüleri

| Giriş Ekranı | Yönetici Paneli | Kitap Ekleme |
| :---: | :---: | :---: |
| ![Giriş](https://via.placeholder.com/300x200?text=Giris+Ekrani) | ![Panel](https://via.placeholder.com/300x200?text=Yonetim+Paneli) | ![Ekleme](https://via.placeholder.com/300x200?text=Kitap+Islemleri) |
*(Kendi ekran görüntülerini eklediğinde buradaki linkleri güncelleyebilirsin)*

## 👨‍💻 Geliştirici

**[Adın Soyadın]**
* Tire Şehit Albay İbrahim Karaoğlanoğlu Anadolu Lisesi - 10. Sınıf Öğrencisi
* [GitHub Profil Linkin]
* [E-posta Adresin]

## 📜 Lisans

Bu proje eğitim amaçlı geliştirilmiştir ve **MIT Lisansı** altında lisanslanmıştır.
