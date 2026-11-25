# Türkiye Konut Fiyat Analizi (2010-2026)

TCMB EVDS verisiyle Türkiye konut fiyatlarının nominal ve enflasyondan arındırılmış (reel) analizi.

## Ne yaptım?
- TCMB EVDS API'den Konut Fiyat Endeksi (Türkiye, İstanbul, Ankara, İzmir) ve TÜFE verisini çektim
- Konut endeksini TÜFE'ye bölerek reel fiyatı hesapladım
- Yıllık reel değişimi ve şehir karşılaştırmasını görselleştirdim

## Öne çıkan bulgular
- 2010'dan beri nominal konut fiyatları yaklaşık 46 kat arttı, reel artış yaklaşık 2,3 kat
- Reel fiyat 2023 ortasında zirve yaptı, sonra %20-25 geriledi
- İzmir reel olarak en çok değer kazanan şehir, Ankara en geride

## Kullanılan araçlar
Python, pandas, matplotlib, TCMB EVDS API

## Veri kaynağı
TCMB EVDS (evds3.tcmb.gov.tr). Reel analiz, TÜFE serisinin bittiği Ocak 2026'ya kadar.

## Sonraki adımlar
- Harita üzerinde il bazlı görselleştirme
- Fiyat tahmin modeli
