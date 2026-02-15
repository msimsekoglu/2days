# 🚀 GitHub Pages'e Yükleme Rehberi

## ADIM 1: GitHub Hesabı Oluştur

1. **https://github.com** adresine git
2. **Sign up** (Kaydol) tıkla
3. Email, kullanıcı adı, şifre gir
4. Email adresini doğrula

---

## ADIM 2: Yeni Repository (Depo) Oluştur

1. GitHub'da **+ ikonu** → **New repository** tıkla
2. **Repository name**: `2days` (veya istediğin isim)
3. **Public** seçili olsun (ücretsiz hosting için)
4. **Add a README** kutucuğunu İŞARETLEME
5. **Create repository** tıkla

---

## ADIM 3: Dosyaları Yükle

### Yöntem 1: Web Üzerinden (Kolay)

1. Yeni oluşan repository sayfasında **uploading an existing file** linkine tıkla
2. **Şu dosyaları** sürükle-bırak veya seç:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `icon-192.svg`
   - `icon-512.svg`
   - `README.md`

3. En altta **Commit message** kutusuna: `İlk yükleme`
4. **Commit changes** (Değişiklikleri kaydet) tıkla

### Yöntem 2: Git ile (İleri Seviye)

Terminal'de:
```bash
cd C:\Users\YourName\Desktop\2days-pwa
git init
git add .
git commit -m "İlk yükleme"
git branch -M main
git remote add origin https://github.com/KULLANICIADIN/2days.git
git push -u origin main
```

---

## ADIM 4: GitHub Pages'i Aktifleştir

1. Repository sayfasında **Settings** (Ayarlar) sekmesine git
2. Sol menüden **Pages** seç
3. **Source** altında:
   - **Branch**: `main` seç
   - **Folder**: `/ (root)` seçili bırak
4. **Save** tıkla
5. ⏳ **2-3 dakika bekle**
6. 🎉 Sayfayı yenile, yeşil kutu ile link göreceksin:
   ```
   Your site is live at https://KULLANICIADIN.github.io/2days/
   ```

---

## ADIM 5: Test Et ve Paylaş!

1. Linke tıkla: `https://KULLANICIADIN.github.io/2days/`
2. Uygulama açılacak ✅
3. Telefonunda dene
4. Arkadaşlarınla paylaş!

---

## 📱 Mobil Cihazlarda Kurulum

### Android (Chrome):
1. Linki aç
2. **⋮ (Menü)** → **Add to Home screen**
3. **Add** tıkla
4. Uygulama ana ekranda! 🎉

### iOS (Safari):
1. Linki aç
2. **Share** ikonu (kutulu ok)
3. **Add to Home Screen**
4. **Add** tıkla
5. Uygulama ana ekranda! 🎉

---

## 🔄 Güncelleme Nasıl Yapılır?

1. Yeni `index.html` dosyasını indir
2. GitHub repository'e git
3. Eski `index.html`'i tıkla
4. **✏️ Edit** (Düzenle)
5. Tüm içeriği sil
6. Yeni içeriği yapıştır
7. **Commit changes** tıkla
8. ⏳ 1-2 dakika sonra site güncellenecek

---

## ❓ Sorun Giderme

### "404 Not Found" hatası
- GitHub Pages'in aktif olduğundan emin ol
- 5 dakika bekle
- Tarayıcı cache'ini temizle (Ctrl+Shift+Del)

### Dosyalar yüklenmiyor
- Dosya adlarının TAMAMEN aynı olduğundan emin ol
- Büyük/küçük harf önemli!
- `index.html` mutlaka küçük harfle

### Site güncellenmiyor
- Cache'i temizle
- Gizli pencere (Incognito) aç
- 5-10 dakika bekle

---

## 🎯 Artık Hazırsın!

✅ Uygulama online  
✅ Herkes erişebilir  
✅ Ücretsiz hosting  
✅ Otomatik güncelleme  

**Linkin:** `https://KULLANICIADIN.github.io/2days/`

Bu linki sosyal medyada paylaşabilirsin! 🚀

---

## 📧 Yardım

Sorun yaşarsan:
- Email: m.simsekoglu@gmail.com
- GitHub Issues: Repository sayfasında "Issues" sekmesi

**Başarılar! 🎉**
