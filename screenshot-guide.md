# Screenshot Guide / Ekran Görüntüsü Rehberi

## Gerekli Cihaz

| Cihaz | Boyut | Zorunlu |
|-------|-------|---------|
| iPhone 15 Pro Max | 1290 × 2796 px | ✅ Evet |

> Not: Sadece iPhone için yayınlanacak. iPad/Mac desteği yok.

---

## Alınacak Ekranlar (Sırasıyla)

### Screenshot 1: Dashboard (Ana Ekran)
**Gösterilecek:** Anlık kazanç göstergesi, günlük durum, hızlı bakış
```
- Simülasyon modu açık olsun (güzel veriler için)
- Kazanç yüzdesi görünür olsun
- Greeting mesajı görünsün
```

### Screenshot 2: Harcamalar Listesi
**Gösterilecek:** Harcama kartları, kategoriler, toplam
```
- Birkaç farklı kategoride harcama olsun
- Renkli kategori ikonları görünsün
```

### Screenshot 3: İstatistikler - Grafikler
**Gösterilecek:** Pasta veya çubuk grafik
```
- "Ay" seçili olsun
- Grafik tam görünsün
- Kategori dağılımı net olsun
```

### Screenshot 4: İstatistikler - Karşılaştırma
**Gösterilecek:** Bu ay vs geçen ay
```
- Karşılaştırma kartı görünsün
- Yüzde değişim görünsün
```

### Screenshot 5: Daha Fazla Menüsü
**Gösterilecek:** Tüm özellikler listesi
```
- Taksitler, abonelikler, birikim hedefleri görünsün
- Menü ikonları renkli olsun
```

### Screenshot 6: Birikim Hedefleri
**Gösterilecek:** Hedef kartları, ilerleme çubukları
```
- Birkaç farklı hedef olsun
- İlerleme yüzdeleri görünsün
```

### Screenshot 7: Borç Takibi
**Gösterilecek:** Alacak/borç kartları
```
- Toplam özet görünsün
- Farklı durumlar (vadesi yaklaşan, ödenen)
```

### Screenshot 8: Widget Önizleme
**Gösterilecek:** Widget'ların nasıl göründüğü
```
- Simulator'da widget ekle
- Home screen'de görüntüle
```

### Screenshot 9: Ayarlar / Tema
**Gösterilecek:** Tema seçenekleri, renk paletleri
```
- Farklı renk teması seçili olsun
- Premium badge görünsün
```

### Screenshot 10: Sesli Harcama Ekleme
**Gösterilecek:** Mikrofon ekranı
```
- VoiceExpenseView açık olsun
- Örnek metin görünsün
```

---

## Screenshot Alma Adımları

### 1. Hazırlık
```bash
# Simulator'ı başlat
open -a Simulator

# iPhone 15 Pro Max seç
# Xcode > Window > Devices and Simulators
```

### 2. Demo Modu Aç
```
Uygulama > Ayarlar > Simülasyon Modu > Başlat
```

### 3. Screenshot Al
```
Her ekranda: ⌘ + S (Masaüstüne kaydeder)
```

### 4. Dosyaları Düzenle
```bash
# Klasör oluştur
mkdir -p ~/Desktop/AppStoreScreenshots/6.7

# Dosyaları yeniden adlandır
# 01_dashboard.png
# 02_expenses.png
# 03_statistics.png
# ...
```

---

## İpuçları

✅ **Status bar'ı temiz tut**
- Saat: 9:41 (Apple standardı)
- Batarya: Dolu
- Sinyal: Tam

✅ **Demo modunu kullan**
- Gerçekçi veriler
- Dolgun görünüm

✅ **Tema tutarlılığı**
- Tüm screenshot'lar aynı temada
- Tercihen açık mod (App Store'da daha iyi görünür)

✅ **Dikey kullan**
- Portrait mode
- Yatay gerekli değil

---

## Profesyonel Mockup (Opsiyonel)

### Araçlar:
- https://previewed.app (ücretsiz)
- https://mockuphone.com (ücretsiz)
- https://rotato.app (ücretli, en iyi)

### Örnek başlık metinleri:
1. "Anlık kazancını takip et"
2. "Harcamalarını kontrol altına al"
3. "Grafiklerle analiz et"
4. "Hedeflerine ulaş"
5. "Widget'larla hızlı erişim"
