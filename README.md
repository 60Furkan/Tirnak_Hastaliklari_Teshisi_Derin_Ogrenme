# Derin Öğrenme Tabanlı Tırnak Hastalıkları Teşhisi ve Sınıflandırılması

Bu depo, tırnak ve ayak hastalıklarının otomatik olarak teşhis edilmesi ve sınıflandırılması amacıyla geliştirilmiş, Evrişimli Sinir Ağları (CNN) tabanlı bir Derin Öğrenme ve Bilgisayarlı Görü (Computer Vision) projesidir. Çalışma, biyoinformatik ve veterinerlik teşhis süreçlerine yüksek doğrulukla katkı sağlamayı hedeflemektedir.

## 📌 Proje Hakkında
Tırnak hastalıklarının erken safhada tespit edilmesi, hayvan sağlığı yönetimi ve erken müdahale için kritik bir öneme sahiptir. Bu projede; tıbbi/görsel veri setlerini işleyen, amaca yönelik veri önişleme adımları uygulayan ve optimize edilmiş sinir ağı mimarileri (EfficientNet/Özel CNN modelleri) kullanarak patolojik durumları sınıflandıran kararlı bir derin öğrenme iş akışı gerçeklenmiştir.

## 🚀 Öne Çıkan Özellikler
* **Gelişmiş Model Mimarisi:** İlgili alandaki hassas ve ince detaylı görüntü sınıflandırma görevleri için optimize edilmiştir.
* **Otomatik Veri İşleme Hattı:** Aşırı öğrenmeyi (overfitting) önlemek amacıyla entegre edilmiş veri önişleme, normalizasyon ve veri artırma (data augmentation) adımları.
* **Kapsamlı Değerlendirme:** Detaylı eğitim günlükleri (logs) ve performans değerlendirme metrikleri.

## 📁 Depo Yapısı
* `notebooka056909b4b.ipynb`: Veri işleme hattını, model eğitimini ve doğrulama adımlarını içeren ana Jupyter Notebook dosyası.
* `test_metrics.txt`: Kayıp (loss) değerleri, kesinlik (precision), duyarlılık (recall) ve doğruluk (accuracy) gibi test sonuçlarını içeren döküman.
* `requirements.txt`: Projenin sorunsuz çalıştırılabilmesi için gerekli olan Python kütüphanelerinin listesi.

## 🛠️ Kurulum ve Çalıştırma

1. **Depoyu Klonlayın:**
```bash
   git clone [https://github.com/60Furkan/Tirnak_Hastaliklari_Teshisi_Derin_Ogrenme.git](https://github.com/60Furkan/Tirnak_Hastaliklari_Teshisi_Derin_Ogrenme.git)
   cd Tirnak_Hastaliklari_Teshisi_Derin_Ogrenme
