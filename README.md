# UMRP - Makina Maliyet Analizi (HTML Demo)

Bu repo, üretilen makinalar için **BOM (Bill of Material) + işçilik + gider sabitleri** üzerinden maliyet analizi yapan tek sayfalık bir HTML demo içerir.

## Özellikler

- BOM satırı ekleme/silme
- Parça bazında para birimi (TRY/USD/EUR) ve kur dönüşümü
- Metal / Amelta malzeme sabit çarpanları
- İşçilik kalemleri:
  - Kaynak
  - Talaşlı imalat
  - Montaj
  - Boya
- Elektrik, su, yakıt giderleri
- Aylık sigorta giderinin makina başına dağıtılması
- Toplamların anlık hesaplanması

## Çalıştırma

Tarayıcıda doğrudan `index.html` dosyasını açabilirsiniz.

Alternatif olarak:

```bash
python3 -m http.server 8000
```

Ardından `http://localhost:8000` adresine gidin.
