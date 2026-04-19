# powerbi-borsa-analizi
# Borsa Analizi Dashboard — Power BI

Bu proje, 7 büyük teknoloji şirketinin **2020-2024 yılları arasındaki hisse senedi verilerini** analiz eden interaktif bir Power BI dashboard'udur.

---

## Proje Önizlemesi

![Dashboard Preview](dashboard_preview.png)

---

## Analiz Edilen Hisseler

| Ticker | Şirket |
|--------|--------|
| AAPL | Apple |
| MSFT | Microsoft |
| TSLA | Tesla |
| AMZN | Amazon |
| GOOGL | Google |
| NVDA | NVIDIA |
| META | Meta |

---

## Dashboard İçeriği

- **KPI Kartları** — Ortalama kapanış fiyatı, en yüksek fiyat, en düşük fiyat, toplam hacim
- **Çizgi Grafik** — 2020-2024 yıllık ortalama kapanış fiyatı trendi
- **Sütun Grafik** — Hisse başına ortalama işlem hacmi karşılaştırması
- **Dilimleyici** — Ticker bazlı interaktif filtreleme

---

## Dosyalar

```
powerbi-borsa-analizi
├── BorsaAnalizi_Dashboard.pbix   # Power BI dashboard dosyası
├── BorsaAnalizi_PowerBI.xlsx     # Ham veri seti
└── README.md                     # Proje açıklaması
```

---

## Veri Seti

`BorsaAnalizi_PowerBI.xlsx` dosyası 3 sayfa içermektedir:

| Sayfa | Açıklama | Satır Sayısı |
|-------|----------|--------------|
| Tum_Veriler | Tüm hisselerin günlük verileri | ~9.000+ |
| Ozet | Hisse başına 5 yıllık özet | 7 |
| AAPL, MSFT... | Her hisse için ayrı sayfa | — |

**Sütunlar:** Tarih, Açılış, En Yüksek, En Düşük, Kapanış, Hacim, Günlük Getiri %, MA20, MA50

---

## Kullanılan Araçlar

- **Power BI Desktop** — Dashboard tasarımı ve görselleştirme
- **Python (openpyxl)** — Veri üretimi ve Excel dosyası oluşturma
- **Excel (.xlsx)** — Veri kaynağı

---

## Öne Çıkan Bulgular

- **NVDA** 2023 sonrası en yüksek büyümeyi gösterdi (AI boom etkisi)
- **MSFT** 2022'de sert düşüş yaşadı, 2024'te güçlü toparlandı
- **TSLA** en yüksek volatiliteye sahip hisse oldu
- Tüm hisseler benzer işlem hacmi seviyelerinde seyretti

