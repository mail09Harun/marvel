# 🎬 Marvel İzleme Takibi

Marvel Sinematik Evreni (MCU) filmlerini ve dizilerini takip etmek için modern, mobil uyumlu Progressive Web App (PWA).

## ✨ Özellikler

- 📱 **PWA Desteği** - Ana ekrana eklenebilir, uygulama gibi çalışır
- 🎯 **İzleme Takibi** - İzlediğiniz içerikleri işaretleyin
- 📊 **İlerleme Göstergesi** - Yüzde bazında ilerlemenizi görün
- 🎨 **Modern Tasarım** - Gradient arka planlar ve akıcı animasyonlar
- 🔍 **Güçlü Filtreleme**:
  - Tür (Film/Dizi)
  - İzlenme durumu
  - Aile uygun içerik
  - Faz bazlı filtreleme
  - Sıralama (Yayın/Kronolojik)
- 🖼️ **Gerçek Film Afişleri** - Tüm içerikler için orijinal posterler
- 💾 **Veri Kalıcılığı** - LocalStorage ile veriler saklanır
- 📴 **Offline Çalışma** - Service Worker ile offline destek

## 🚀 Kurulum

### GitHub'a Yükleme

```bash
git clone <repo-url>
cd marvel-tracker
```

### Vercel'de Yayınlama

1. [Vercel](https://vercel.com) hesabınıza giriş yapın
2. "New Project" butonuna tıklayın
3. GitHub reponuzu seçin
4. Deploy butonuna tıklayın

Vercel otomatik olarak `index.html` dosyasını algılayacak ve yayınlayacaktır.

## 📱 Mobil Kullanım

### iOS (Safari)
1. Uygulamayı Safari'de açın
2. Paylaş butonuna (⬆️) tıklayın
3. "Ana Ekrana Ekle" seçeneğini seçin

### Android (Chrome)
1. Uygulamayı Chrome'da açın
2. Menü butonuna (⋮) tıklayın
3. "Ana ekrana ekle" seçeneğini seçin

## 🎯 Kullanım

- **İzledim İşaretleme**: Her kartın sağ üst köşesindeki checkbox'ı işaretleyin
- **Detay Görüntüleme**: Kartın herhangi bir yerine tıklayarak açıklamayı görebilirsiniz
- **Filtreleme**: Üst kısımdaki filtreleri kullanarak içerikleri süzün
- **Sıralama**: Yayın sırası veya kronolojik sıra arasında seçim yapın

## 📦 Dosya Yapısı

```
marvel-tracker/
├── index.html          # Ana uygulama dosyası
├── manifest.json       # PWA manifest dosyası
├── sw.js              # Service Worker
└── README.md          # Bu dosya
```

## 🛠️ Teknolojiler

- HTML5
- CSS3 (Gradient, Flexbox, Animations)
- Vanilla JavaScript
- LocalStorage API
- Service Worker API
- Progressive Web App (PWA)

## 📊 İçerik

Uygulama **47 Marvel içeriği** içerir:
- **Faz 1**: 6 film
- **Faz 2**: 6 film
- **Faz 3**: 11 film
- **Faz 4**: 16 film/dizi
- **Faz 5**: 8 film/dizi

## 🎨 Tasarım Özellikleri

- Modern ve minimal arayüz
- Marvel temalı renk paleti (Kırmızı, Sarı, Mavi)
- Responsive tasarım (Mobil-first)
- Smooth animasyonlar
- Gradient efektler
- Hover ve click etkileşimleri

## 📝 Lisans

MIT License - İstediğiniz gibi kullanabilirsiniz!

## 🤝 Katkıda Bulunma

Pull request'ler kabul edilir. Büyük değişiklikler için lütfen önce bir issue açın.

---

**Not**: Bu uygulama Marvel Studios ile ilişkili değildir. Sadece hayranlar için yapılmış bir takip uygulamasıdır.
