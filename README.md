# Organic Foods Shop - Responsive Web Projesi

Bu proje, modern ve responsive bir organik gıda e-ticaret web sitesi tasarımını içermektedir. SASS kullanılarak geliştirilmiş olup, BEM metodolojisi ile yapılandırılmıştır.

## 🚀 Özellikler

- Responsive tasarım (mobil, tablet ve masaüstü uyumlu)
- Modern ve kullanıcı dostu arayüz
- SASS ile modüler CSS yapısı
- BEM metodolojisi ile organize edilmiş kod yapısı
- Bootstrap grid sistemi entegrasyonu
- Animasyonlu UI elementleri
- Video arka plan desteği
- Form validasyonları

## 🛠️ Kullanılan Teknolojiler

- HTML5
- SASS/SCSS
- Bootstrap 5.3.3
- Google Fonts (Inter, Lato, Rubik)
- CSS Animations
- Responsive Design

## 📁 Proje Yapısı

```
advanced-css/
├── css/
│   └── style.css
├── sass/
│   ├── base/
│   │   ├── _base.scss
│   │   ├── _animation.scss
│   │   ├── _typography.scss
│   │   └── _utilities.scss
│   ├── components/
│   │   ├── _button.scss
│   │   ├── _composition.scss
│   │   ├── _feature-box.scss
│   │   ├── _card.scss
│   │   ├── _testimonial.scss
│   │   └── _bg-video.scss
│   ├── layout/
│   │   ├── _header.scss
│   │   └── _grid.scss
│   ├── pages/
│   │   └── _home.scss
│   └── main.scss
├── images/
├── icons/
└── index.html
```

## 🚀 Kurulum

1. Projeyi klonlayın:
```bash
git clone [proje-url]
```

2. SASS'ı global olarak yükleyin (eğer yüklü değilse):
```bash
npm install -g sass
```

3. SASS dosyalarını CSS'e derleyin:
```bash
sass sass/main.scss css/style.css --watch
```

4. `index.html` dosyasını bir web tarayıcısında açın.

## 🎨 Bileşenler

- Header bölümü
- Hakkımızda bölümü
- Özellikler bölümü
- Ürün kartları
- Müşteri yorumları
- Kayıt formu

## 📱 Responsive Breakpoints

- Mobile: < 600px
- Tablet: 600px - 900px
- Desktop: > 900px

## 🎯 BEM Metodolojisi

Proje BEM (Block Element Modifier) metodolojisi kullanılarak yapılandırılmıştır:

```scss
.block {
    &__element {
        &--modifier {
            // styles
        }
    }
}
```

## 🤝 Katkıda Bulunma

1. Bu depoyu fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun


## İletişim

Proje Sahibi - [@BT-maker](https://github.com/BT-maker)

Proje Linki: [https://github.com/BT-maker/advanced-css](https://github.com/BT-maker/advanced-css) 


# advanced-css
