# Kampüs Etkinlikleri — Sprint 3

Bu klasör Sprint 3 — JavaScript ve DOM gerekliliklerine göre hazırlanmıştır.

## Çalıştırma

ES module kullanıldığı için dosyaları `file://` ile açmayın. VS Code Live Server ya da başka bir yerel HTTP sunucusu kullanın.

Örnek:

```bash
cd sprint3
python3 -m http.server 5500
```

Sonra `http://127.0.0.1:5500/` adresini açın.

## Sprint 3

- `js/data.js`: 6 etkinlik ve benzersiz id'ler
- `js/event-list.js`: kart üretimi, ana sayfada 2 etkinlik, arama + kategori filtresi
- `js/event-detail.js`: `?id=` ile dinamik detay ve geçersiz id kontrolü
- `js/event-form.js`: özel doğrulama, hata/başarı mesajı ve güncelleme formunun id ile doldurulması
- `css/2221031010.css`: öğrenci numarasına göre tema; son hane 0 olduğu için Arial
- localStorage, jQuery veya framework kullanılmamıştır

## Kontrol adresleri

- `etkinlik-detay.html?id=event-3`
- `etkinlik-detay.html?id=event-99`
- `etkinlik-guncelle.html?id=event-4`
- `etkinlik-guncelle.html` (id'siz uyarı)

## Teslim

Vercel'de **Root Directory** değerini `sprint3` yapın. Ardından:

```bash
git add .
git commit -m "Sprint3 yapıldı"
git tag sprint-03
git push
git push --tags
```
