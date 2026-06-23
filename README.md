# Derin Öğrenme Tabanlı Tırnak Hastalıkları Teşhisi ve Sınıflandırılması

Bu depo, insan tırnaklarında görülen çeşitli hastalıkların ve anomalilerin otomatik olarak teşhis edilmesi amacıyla geliştirilmiş, Evrişimli Sinir Ağları (CNN) tabanlı bir Derin Öğrenme ve Bilgisayarlı Görü (Computer Vision) projesidir. Çalışma, klinik ve dermatolojik teşhis süreçlerine yardımcı olmayı hedeflemektedir.

## 📌 Proje Hakkında
Tırnak hastalıklarının ve anomalilerinin (mantar enfeksiyonları, sedef reaksiyonları vb.) erken safhada ve doğru teşhis edilmesi, tedavi süreçleri için kritik önem taşır. Bu projede; tırnak görüntülerinden oluşan medikal veri setlerini işleyen, amaca yönelik veri önişleme ve veri artırma (data augmentation) adımları uygulayan ve derin öğrenme mimarileri (EfficientNet/CNN) kullanan kararlı bir sınıflandırma modeli gerçeklenmiştir.

## 🚀 Öne Çıkan Özellikler
* **Gelişmiş Model Mimarisi:** Medikal görüntü sınıflandırma ve ince detaylı öznitelik çıkarımı için optimize edilmiş derin öğrenme modelleri.
* **Veri İşleme Hattı:** Görselleri model eğitimine hazırlayan; normalizasyon ve aşırı öğrenmeyi (overfitting) önleyici veri artırma adımları.
* **Kapsamlı Değerlendirme:** Eğitim sürecine ait kayıp (loss) ve doğruluk (accuracy) takibi ile test metriklerinin raporlanması.

## 📁 Depo Yapısı
* `notebooka056909b4b.ipynb`: Veri işleme, model eğitimi, doğrulama ve test adımlarını içeren ana Jupyter Notebook dosyası.
* `test_metrics.txt`: Modelin test aşamasındaki başarı sonuçlarını (kesinlik, duyarlılık, doğruluk vb.) içeren çıktı dosyası.
* `requirements.txt`: Projenin sorunsuz çalıştırılabilmesi için gerekli olan Python kütüphanelerinin listesi.

## 🛠️ Kurulum ve Çalıştırma

1. **Depoyu Klonlayın:**
```bash
   git clone [https://github.com/60Furkan/Tirnak_Hastaliklari_Teshisi_Derin_Ogrenme.git](https://github.com/60Furkan/Tirnak_Hastaliklari_Teshisi_Derin_Ogrenme.git)
   cd Tirnak_Hastaliklari_Teshisi_Derin_Ogrenme
