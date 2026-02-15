# 2Days - Alışkanlık Takip Uygulaması

**Slogan:** *Miss once, never twice*  
**Versiyon:** 26.02  
**Geliştirici:** Murat Şimşekoğlu

---

## 📖 Hakkında

2Days, 49 günlük alışkanlık oluşturma sürecini oyunlaştıran bir web uygulamasıdır. "Bir gün kaçırmak zayıflık değil, iki gün üst üste kaçırmak bir tercihtir" felsefesi üzerine kurulmuştur.

**Temel Prensipler:**
- ✅ Asla iki gün üst üste boş geçirme
- ✅ Disiplin + Esneklik = Kalıcı Alışkanlık
- ✅ Joker sistemi ile gerçekçi yaklaşım
- ✅ 7G kurtarma görevi ile ikinci şans

---

## 🎮 Özellikler

### ✨ Temel Özellikler
- **49 Günlük Quest Sistemi**: Bilimsel olarak kanıtlanmış alışkanlık oluşturma süresi
- **Çoklu Quest Yönetimi**: Aynı anda birden fazla alışkanlık takibi
- **Joker Sistemi**: Başlangıçta 1 joker, her 14 gün streak'te +1
- **7G Kurtarma Görevi**: İki boş gün sonrası 7 gün peş peşe tamamlama şansı
- **Otomatik Takvim Uzatma**: Quest bitiminde <7 gün kalırsa +7 gün ekleme
- **Streak Takibi**: Kesintisiz gün sayısı ve ödüller
- **Arşiv Sistemi**: Tamamlanan ve başarısız questlerin geçmişi

### 🎨 Kullanıcı Deneyimi
- Modern neon tasarım
- Responsive (mobil uyumlu)
- Konfeti animasyonları
- Modal sistemler
- PWA desteği (offline çalışma)
- Veri yedekleme/geri yükleme

### 🔧 Geliştirici Özellikleri
- Test modu (şifre korumalı)
- Debug araçları
- Export/Import sistemi
- LocalStorage veri saklama

---

## 🚀 Kullanım

### Web Tarayıcısında
1. `index.html` dosyasını çift tıklayarak aç
2. VEYA bir web sunucusunda çalıştır

### PWA Olarak (Tavsiye Edilen)
1. Chrome/Edge tarayıcısında aç
2. Adres çubuğundaki **+** ikonuna tıkla
3. "Yükle" veya "Ana ekrana ekle" seç
4. Artık uygulama gibi çalışır! 📱

### Mobil (Android/iOS)
1. Tarayıcıda aç
2. **Menü → Ana ekrana ekle**
3. Uygulama simgesi ana ekranda oluşur

---

## 📊 Nasıl Çalışır?

### Kurallar
1. **Başlangıç**: 1 joker hakkınız var
2. **Her Gün**: Alışkanlığınızı tamamlayın
3. **Boş Gün**: Bir gün kaçırabilirsiniz
4. **İki Boş Gün**: 
   - Joker kullan VEYA
   - 7G görevi başlat (7 gün peş peşe)
5. **14 Gün Streak**: Yeni joker kazan
6. **49 Gün**: Quest tamamlandı! 🎉

### Joker Kuralları
- Peş peşe kullanılamaz
- Sadece "game over"ı engeller
- Streak'i kesmez

### 7G Görevi
- 7 gün üst üste tamamlama zorunluluğu
- Başarısız olursan quest iptal
- Başarılı olursan devam

---

## 💾 Veri Yönetimi

### Yedekleme
1. **Hakkında** → **Veri Yönetimi**
2. **Dışa Aktar** tıkla
3. JSON dosyası indirilir
4. Güvenli yerde sakla

### Geri Yükleme
1. **Hakkında** → **Veri Yönetimi**
2. **İçe Aktar** tıkla
3. JSON dosyasını seç
4. Veriler yüklenir

**Önemli:** Tarayıcı verilerini temizleme, verilerinizi siler. Düzenli yedekleme yapın!

---

## 🛠️ Teknik Detaylar

### Teknolojiler
- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **Veri Saklama**: LocalStorage
- **PWA**: Service Worker, Web App Manifest
- **Tasarım**: Responsive, Neon UI

### Dosya Yapısı
```
2days-pwa/
├── index.html              # Ana uygulama
├── manifest.json           # PWA manifest
├── service-worker.js       # Offline destek
├── icon-192.svg           # Uygulama ikonu (192x192)
├── icon-512.svg           # Uygulama ikonu (512x512)
└── README.md              # Bu dosya
```

### LocalStorage Yapısı
```javascript
{
  "multiQuestData": {
    "activeQuests": [...],
    "archivedQuests": [...],
    "currentQuestId": "..."
  },
  "debugMode": false
}
```

## 📄 Lisans

Bu proje **Murat Şimşekoğlu** tarafından geliştirilmiştir.

**İletişim:** m.simsekoglu@gmail.com

---

## 🙏 Teşekkürler

Bu uygulamayı kullandığınız için teşekkürler!

**Unutmayın:**
> "Motivasyon başlatır. Disiplin bitirir. Sen sadece iki gün üst üste vazgeçme."

---

**Versiyon:** 26.02  
**Son Güncelleme:** {{ BUGÜN }}  
**Website:** Coming soon...
