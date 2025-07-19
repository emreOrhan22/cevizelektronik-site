# Ceviz Elektronik - Modern Web Sitesi

Ceviz Elektronik için tasarlanmış modern, responsive ve profesyonel web sitesi. Elektronik onarım ve otomasyon hizmetleri sunan şirket için özel olarak geliştirilmiştir.

## 🚀 Özellikler

### Modern Tasarım
- **Responsive Design**: Tüm cihazlarda mükemmel görünüm
- **Modern UI/UX**: Kullanıcı dostu arayüz tasarımı
- **Smooth Animations**: Sayfa geçişleri ve etkileşimler
- **Gradient Effects**: Modern gradient renk geçişleri

### Teknik Özellikler
- **React 19**: En güncel React sürümü
- **Vite**: Hızlı geliştirme ve build süreci
- **Tailwind CSS**: Modern CSS framework
- **React Icons**: Zengin ikon kütüphanesi
- **Intersection Observer**: Scroll animasyonları

### Bileşenler
- **Hero Section**: Etkileyici ana sayfa bölümü
- **About Section**: Şirket hakkında detaylı bilgi
- **Services Section**: Hizmet kartları ve modal'lar
- **Gallery Section**: Proje galerisi ve filtreleme
- **Contact Section**: İletişim formu ve bilgiler
- **Footer**: Sosyal medya ve linkler

## 🛠 Teknoloji Stack'i

```json
{
  "react": "^19.1.0",
  "react-dom": "^19.1.0",
  "react-icons": "^5.5.0",
  "react-router-dom": "^7.7.0",
  "tailwindcss": "^4.1.11",
  "vite": "^7.0.4"
}
```

## 📁 Proje Yapısı

```
src/
├── components/          # Yeniden kullanılabilir bileşenler
│   ├── Header.jsx      # Navigasyon ve logo
│   ├── HeroSection.jsx # Ana banner bölümü
│   ├── About.jsx       # Hakkımızda bölümü
│   ├── Services.jsx    # Hizmetler bölümü
│   ├── Gallery.jsx     # Galeri bölümü
│   ├── Contact.jsx     # İletişim bölümü
│   └── Footer.jsx      # Alt bilgi
├── pages/              # Sayfa bileşenleri
│   └── Home.jsx        # Ana sayfa
├── assets/             # Görseller ve medya
└── index.css           # Global stiller
```

## 🎨 Tasarım Özellikleri

### Renk Paleti
- **Primary**: Blue (#2563eb)
- **Secondary**: Purple (#764ba2)
- **Accent**: Orange (#f59e0b)
- **Success**: Green (#10b981)
- **Background**: White & Gray tones

### Tipografi
- **Font**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700, 800
- **Responsive**: Clamp() fonksiyonu ile

### Animasyonlar
- **Fade In Up**: Sayfa yükleme animasyonları
- **Slide In Left**: Yan kayma efektleri
- **Hover Effects**: Etkileşim animasyonları
- **Smooth Transitions**: Yumuşak geçişler

## 🚀 Kurulum ve Çalıştırma

### Gereksinimler
- Node.js 18+ 
- npm veya yarn

### Kurulum
```bash
# Projeyi klonlayın
git clone [repository-url]
cd ceviz-elektronik

# Bağımlılıkları yükleyin
npm install

# Geliştirme sunucusunu başlatın
npm run dev

# Production build
npm run build
```

### Komutlar
```bash
npm run dev      # Geliştirme sunucusu
npm run build    # Production build
npm run preview  # Build önizleme
npm run lint     # ESLint kontrolü
```

## 📱 Responsive Tasarım

### Breakpoint'ler
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

### Özellikler
- **Mobile-First**: Mobil öncelikli tasarım
- **Flexible Grid**: Esnek grid sistemi
- **Touch-Friendly**: Dokunmatik cihaz uyumlu
- **Performance**: Optimize edilmiş performans

## 🎯 SEO ve Performans

### SEO Optimizasyonu
- **Semantic HTML**: Anlamlı HTML yapısı
- **Meta Tags**: Sayfa meta bilgileri
- **Alt Text**: Görsel açıklamaları
- **Structured Data**: Yapılandırılmış veri

### Performans
- **Lazy Loading**: Görsel yükleme optimizasyonu
- **Code Splitting**: Kod bölme
- **Image Optimization**: Görsel optimizasyonu
- **Minification**: Kod sıkıştırma

## 🔧 Özelleştirme

### Renk Değişiklikleri
```css
:root {
  --primary-color: #2563eb;
  --secondary-color: #64748b;
  --accent-color: #f59e0b;
}
```

### Font Değişiklikleri
```css
body {
  font-family: 'Inter', sans-serif;
}
```

### Animasyon Hızları
```css
--transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
```

## 📞 İletişim

Proje hakkında sorularınız için:
- **E-posta**: info@ceviz-elektronik.com
- **Telefon**: +90 212 555 0123
- **Adres**: Kadıköy, İstanbul

## 📄 Lisans

Bu proje Ceviz Elektronik için özel olarak geliştirilmiştir. Tüm hakları saklıdır.

---

**Geliştirici**: Modern Web Teknolojileri  
**Tarih**: 2024  
**Versiyon**: 2.0.0
