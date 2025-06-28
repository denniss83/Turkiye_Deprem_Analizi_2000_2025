# 🇹🇷 Türkiye Deprem Analizi (2000–2025)

## ⚠️ Uyarı

> Bu analiz, **Python programlama ve veri görselleştirme pratiği yapmak amacıyla, bireysel öğrenme sürecim kapsamında** hazırlanmıştır.  
> Kullanılan veriler **AFAD’ın herkese açık deprem arşivinden** alınmıştır.  
> Çalışmanın herhangi bir **resmî kurumla bağlantısı yoktur** ve **erken uyarı ya da bilimsel tahmin amacı taşımaz**.  
> Amaç, veri analizi becerileri geliştirmek ve farkındalık oluşturan görselleştirmeler üretmektir.

---

## 📊 Kullanılan Veriler

- **Kaynak:** [AFAD Deprem Dairesi Başkanlığı](https://deprem.afad.gov.tr)
- **Kapsam:** 2000–2025 arası Türkiye genelindeki tüm depremler

> Veriler üzerinde **herhangi bir temizlik veya filtreleme işlemi uygulanmamıştır**. Ham haliyle, olduğu gibi analiz edilmiştir.

---

## 🗺️ Yapılan Analizler

- Toplam deprem sayısı, 3.5 ve 5.0 üzeri deprem sayısı
- En büyük ilk 20 deprem
- En çok deprem olan ilk 10 il / ilçe
- Deprem yoğunluğuna göre Türkiye haritası (renkli)
- Yıllara ve aylara göre deprem dağılımı
- Derinliğe ve büyüklüğe göre histogramlar
- 5 lokasyonda yıllık deprem trendi

---

## 🛠️ Kullanılan Kütüphaneler

| Kütüphane            | Açıklama                                          |
|----------------------|---------------------------------------------------|
| `pandas`             | Veri yükleme, işleme ve analiz                    |
| `numpy`              | Sayısal işlemler, istatistiksel hesaplamalar     |
| `matplotlib.pyplot`  | Temel grafik çizimleri                            |
| `seaborn`            | İstatistiksel görselleştirme                      |
| `datetime`           | Tarih ve zaman işlemleri                          |
| `folium`             | Harita tabanlı görselleştirme                     |
| `folium.plugins`     | Marker cluster (yoğunluklu harita işaretleme)     |
| `geopandas`          | GeoJSON ve coğrafi veri yönetimi                 |
| `plotly.express`     | Etkileşimli grafikler                             |
| `tabulate`           | Terminal / metin çıktısı için tablo oluşturma     |
| `warnings`           | Uyarı mesajlarını bastırmak için                  |
| `requests`           | İnternetten veri çekmek (ör. GeoJSON)            |
| `json`               | JSON ve GeoJSON verilerini işlemek için          |


---

## 👨‍💻 Hazırlayan

Deniz Atabey  

---
