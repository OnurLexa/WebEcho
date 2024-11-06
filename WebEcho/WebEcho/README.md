# WebEcho

WebEcho, herhangi bir web sitesini hızlı ve etkili bir şekilde klonlamak için geliştirilmiş bir araçtır. Bu araç, belirttiğiniz bir URL üzerinden sayfa ve görüntü içeriklerini indirip yerel bir kopya oluşturur.

## Özellikler

- **Tam Sayfa İndirimi:** Web sitesindeki tüm sayfa bağlantılarını analiz ederek, her sayfanın bir kopyasını oluşturur.
- **Görsellerin Kaydedilmesi:** Web sayfasında yer alan tüm görselleri belirli bir klasöre indirir.
- **Otomatik Klasör Yapısı:** Web sitesinin dosya ve klasör yapısını korur, tüm dosyaları organize eder.
- **Loglama:** Çalışma sürecindeki adımlar, `image_scraper.log` dosyasına kaydedilir.

## Kurulum

Projeyi bilgisayarınıza klonlayarak başlayabilirsiniz.

```bash
git clone https://github.com/kullanici/WebEcho.git
cd WebEcho

## Gerekli Python paketlerini kurmak için:
- pip install -r requirements.txt
