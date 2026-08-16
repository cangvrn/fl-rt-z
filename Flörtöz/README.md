# Flörtöz

Sevgililerin güne başlarken ve günü kapatırken birbirine ulaşmasını unutmaması için hazırlanmış küçük bir hatırlatma ve flört asistanı. Dünya işi araya girse de günaydın, gün içi ve iyi geceler mesajlarını hatırlatır; mesaj, mekan ve hediye önerileri sunar.

## Özellikler

- **Bugün**: saate göre günaydın / gün içi / iyi geceler mesajı önerir, hatırlatıcı saatleri ayarlanabilir
- **Mesajlar**: günaydın, iyi geceler, iltifat ve sohbet açıcı mesaj kütüphanesi
- **Mekan**: buluşma yeri önerileri (puan, fiyat seviyesi, yoğunluk ve ulaşım notlarıyla)
- **Hediye**: ilgi alanı ve bütçeye göre hediye önerisi
- **Özel Günler**: doğum günü, ilk buluşma gibi tarihler için geri sayım
- **Regl Takvimi**: tahmini döngü takibi ve o dönemde nasıl davranılacağına dair genel öneriler
- **Favoriler**: beğenilen mesajları kaydetme

## Teknik

Tek dosyalık bir HTML/CSS/JS uygulaması, veri saklama için `window.storage` kullanır. Bir PWA (Progressive Web App) olarak yapılandırılmıştır (`manifest.json` + `sw.js`), bu sayede tarayıcıdan "ana ekrana ekle" ile ya da Bubblewrap/TWA aracılığıyla bir Android uygulamasına dönüştürülüp Play Store'da yayınlanabilir.

## Dosyalar

- `unutma.html` — uygulamanın kendisi
- `manifest.json` — PWA yapılandırması
- `sw.js` — service worker
- `icons/` — uygulama ikonları

## Not

Bu bir kişisel proje / MVP'dir. Mesaj gönderimi otomatik değildir — uygulama sana hazır bir metin önerir, sen kopyalayıp WhatsApp veya SMS'ten gönderirsin.
