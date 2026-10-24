# Türkiye'de Enflasyon, Döviz Kuru ve Faiz Oranlarının Ekonomik Büyüme Üzerindeki Etkisi (2015-2025)

2015-2025 dönemi çeyreklik verilerle (44 gözlem) enflasyon, USD/TL kuru değişimi ve repo faizinin GSYH büyümesi üzerindeki etkisini inceleyen SPSS analizi.

## Veri
TCMB EVDS üzerinden alınan çeyreklik seriler:
- **Enflasyon:** TÜFE (Genel, 2003=100), yıllık % değişim, çeyrek ortalaması
- **Döviz kuru:** USD/TL (döviz alış), yıllık % değişim, çeyrek ortalaması
- **Faiz:** TCMB repo faizi (2-14 gün, ağırlıklı ortalama), düzey, çeyrek ortalaması
- **Büyüme:** GSYH (üretim yöntemiyle, zincirlenmiş hacim), yıllık % değişim

## Yöntem
Çoklu doğrusal regresyon: büyüme ~ enflasyon + kur değişimi + repo faizi

## Bulgular
- Üç değişkenin de büyüme üzerinde istatistiksel olarak anlamlı bir etkisi bulunmadı (tüm p değerleri 0,05'in üzerinde)
- Model açıklama gücü çok düşük (R² = 0,016), F testi anlamsız (p = 0,88)
- Bu dönemde enflasyon ve kur çok oynak olmasına rağmen büyüme görece yüksek kaldı

## Sınırlılıklar
- Enflasyon, kur ve faiz serileri durağan değil (ADF testi), sonuçlar yanıltıcı regresyon riski taşıyor
- Hata terimlerinde hafif otokorelasyon var (Durbin-Watson = 1,32)
- Enflasyon ile kur arasında yüksek korelasyon var (0,76), VIF değerleri kabul edilebilir sınırda
- Örneklem küçük (44 çeyrek), tek ülke, pandemi ve 2018-2022 şokları modelde ayrıca kontrol edilmedi
- Etkiler gecikmeli olabilir, gecikmeli modeller denenmedi

## Dosyalar
- `turkiye_makro_2015_2025.sav`: SPSS veri dosyası
- `turkiye_makro_2015_2025.csv`: aynı veri, CSV formatında
- SPSS çıktısı (PDF ya da HTML)

## Araçlar
SPSS, TCMB EVDS[OUTPUT.doc](https://github.com/user-attachments/files/33908582/OUTPUT.doc)
[turkiye_makro_2015_2025.csv](https://github.com/user-attachments/files/33908558/turkiye_makro_2015_2025.csv)




