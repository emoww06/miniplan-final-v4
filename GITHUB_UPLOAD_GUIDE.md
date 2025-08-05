# 🚀 GitHub'a Yükleme Rehberi

## 1. GitHub'da Yeni Repository Oluşturun
- GitHub.com'a gidin
- **"New repository"** tıklayın
- **Repository name:** `miniplan-final-v2`
- **Public** seçin
- **"Create repository"** tıklayın

## 2. Dosyaları Yükleyin
**SADECE BU DOSYALARI YÜKLEYİN:**

### Zorunlu Dosyalar (Root'a yükleyin):
- ✅ `index.html` - Ana uygulama
- ✅ `manifest.json` - PWA manifest
- ✅ `sw.js` - Service Worker
- ✅ `styles.css` - CSS stilleri
- ✅ `icon.png` - Uygulama ikonu (512x512 PNG)

### Yüklemeyin:
- ❌ `GITHUB_UPLOAD_GUIDE.md` (bu dosya)
- ❌ Klasörler (screenshots, icons, web, .vscode, .idea, lib)
- ❌ Diğer tüm dosyalar

## 3. GitHub Pages'i Aktifleştirin
- Repository'de **Settings** sekmesine gidin
- Sol menüde **Pages** tıklayın
- **Source:** "Deploy from a branch" seçin
- **Branch:** "main" seçin
- **Folder:** "/ (root)" seçin
- **Save** tıklayın

## 4. URL'yi Alın
- `https://kullaniciadi.github.io/miniplan-final-v2/` şeklinde URL alacaksınız

## 5. PWA Builder'da Test Edin
- https://www.pwabuilder.com adresine gidin
- URL'nizi yapıştırın
- **"Start"** tıklayın
- APK oluşturun

## 6. Sorun Giderme
Eğer hata alırsanız:
1. Tüm dosyaların root'ta olduğundan emin olun
2. GitHub Pages'in aktif olduğunu kontrol edin
3. URL'nin çalıştığını tarayıcıda test edin
4. PWA Builder'da tekrar deneyin

## ✅ Başarılı Yükleme Sonrası
- GitHub Pages yeşil tik gösterecek
- URL tarayıcıda açılacak
- PWA Builder tüm testleri geçecek
- APK başarıyla oluşturulacak

## 🔧 Icon Sorunu Çözümü
Eğer "Failed to download icon" hatası alırsanız:
1. icon.png dosyasının root'ta olduğundan emin olun
2. Dosya adının tam olarak "icon.png" olduğunu kontrol edin
3. GitHub Pages'in yeniden deploy olmasını bekleyin (5-10 dakika)
4. Tarayıcıda `https://kullaniciadi.github.io/miniplan-final-v2/icon.png` adresini test edin

**�� Hemen başlayın!** 