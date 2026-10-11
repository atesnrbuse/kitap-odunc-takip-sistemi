# 📚 Kitap Ödünç Takip Sistemi
Nesne Yönelimli Programlama (OOP) prensipleriyle geliştirilmiş; kitap envanterini, öğrenci kayıtlarını ve ödünç alma süreçlerini metin tabanlı (`.txt`) dosya üzerinde saklayan konsol uygulaması.

---

## 🚀 Özellikler

- **Kitap & Öğrenci Yönetimi:** Yeni kitap ve öğrenci ekleme, kayıtlı listeleri görüntüleme.
- **Ödünç Alma / İade Mekanizması:** 
  - Kitapların müsaitlik ve ödünç durumunu takip etme.
  - Öğrenci numarası üzerinden kitap eşleştirme ve iade alma.
- **Kalıcı Veri Saklama (File I/O):** Tüm kayıtların `library_data.txt` dosyasına kaydedilmesi ve program açılışında otomatik yüklenmesi.
- **Hata Yönetimi:** Geçersiz menü seçimleri, format hataları ve eksik veri girişlerine karşı `try-except` kontrolleri.

---

## 🛠️ Kullanılan Teknolojiler & Kavramlar

- **Dil:** Python 3.x
- **OOP (Nesne Yönelimli Programlama):** `Book`, `Student`, `LibrarySystem` sınıfları ve `__init__`, `__str__` metotları
- **Dosya İşlemleri (File Handling):** `open()`, veri okuma/yazma, UTF-8 dosya yönetimi
- **Hata Yakalama:** `try-except`, `ValueError`, `FileNotFoundError`

---

## 💻 Kurulum ve Çalıştırma

```bash
python main.py
