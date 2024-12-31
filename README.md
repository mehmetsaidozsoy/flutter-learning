# Sonuç Sorgulama 📱

Excel dosyasından öğrenci sonuçlarını sorgulayan Flutter web uygulaması.

## 🚀 Özellikler
- 🌓 Koyu/Açık tema desteği
- 📊 Excel dosyasından veri okuma
- 🔍 Aday numarası ile sorgulama
- 💻 Web platformu desteği

## 🛠️ Kullanılan Teknolojiler
- Flutter 3.19.0
- Provider (State Management)
- Excel Package
- Material Design 3

## 🏗️ Proje Yapısı
sonucsorgu/
├── lib/
│   ├── main.dart           # Ana uygulama
│   ├── theme/
│   │   ├── app_theme.dart    # Tema tanımlamaları
│   │   └── theme_provider.dart # Tema yönetimi
│   └── services/
│       └── excel_service.dart  # Excel işlemleri
├── test/
│   └── widget_test.dart    # Widget testleri
├── web/
│   └── index.html         # Web entrypoint
└── pubspec.yaml          # Bağımlılıklar

## 🚀 Kurulum
1. Flutter SDK'yı yükleyin
2. Projeyi klonlayın:
   ```bash
   git clone https://github.com/kullaniciadi/sonucsorgu.git
   ```
3. Bağımlılıkları yükleyin:
   ```bash
   flutter pub get
   ```
4. Uygulamayı çalıştırın:
   ```bash
   flutter run -d chrome
   ```

## 📱 Ekran Görüntüleri
[Ekran görüntüleri eklenecek]

## 🤝 Katkıda Bulunma
1. Bu repo'yu fork edin
2. Feature branch oluşturun (`git checkout -b feature/yeniOzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'feat: yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin feature/yeniOzellik`)
5. Pull Request oluşturun

## 📝 Lisans
Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.
