# Basit Uygulamalar

React Native (Expo) ile geliştirilen mobil uygulamalar koleksiyonu.

## Uygulamalar

### 1. HabitTracker
Alışkanlık takip uygulaması - Günlük alışkanlıklarınızı takip edin, streak'ler oluşturun ve seviye atlayın.

**Özellikler:**
- Alışkanlık oluşturma (isim, renk, sıklık)
- Günlük/Haftalık takip
- Streak sistemi (ardışık gün takibi)
- Streak Freeze (kaçırılan günleri kurtarma)
- XP & Level gamification
- Push notifications (hatırlatıcılar)
- İstatistikler ve grafikler
- Arşiv özelliği
- Dark mode tasarım

**Teknolojiler:** React Native, Expo, TypeScript, Context API, AsyncStorage

### 2. FocusFlow
Pomodoro timer uygulaması - Odaklanma seanslarınızı yönetin ve verimliliğinizi artırın.

**Özellikler:**
- Pomodoro timer (25dk focus, 5dk kısa mola, 15dk uzun mola)
- Özelleştirilebilir süreler
- Circular progress animasyonu
- Görev yönetimi
- Ses efektleri (Web + Native)
- Haptic feedback
- Günlük/Haftalık istatistikler
- Push notifications
- Auto-start seçenekleri
- Dark mode tasarım

**Teknolojiler:** React Native, Expo, TypeScript, Zustand, Reanimated, expo-av

## Kurulum

```bash
# HabitTracker
cd HabitTracker
npm install
npm start

# FocusFlow
cd FocusFlow
npm install
npm start
```

## Çalıştırma

```bash
# Web'de çalıştır
npm start -- --web

# iOS simulator (macOS gerekli)
npm start -- --ios

# Android emulator
npm start -- --android
```

## Proje Yapısı

```
basit-uygulamalar/
├── HabitTracker/
│   ├── src/
│   │   ├── components/
│   │   ├── screens/
│   │   ├── context/
│   │   ├── navigation/
│   │   ├── utils/
│   │   ├── types/
│   │   └── constants/
│   ├── assets/
│   └── package.json
│
├── FocusFlow/
│   ├── src/
│   │   ├── components/
│   │   ├── screens/
│   │   ├── store/
│   │   ├── services/
│   │   ├── navigation/
│   │   ├── types/
│   │   └── constants/
│   ├── assets/
│   └── package.json
│
└── README.md
```

## Geliştirme Durumu

| Uygulama | Versiyon | Durum |
|----------|----------|-------|
| HabitTracker | V3 | Tamamlandı |
| FocusFlow | V1 | Tamamlandı |

## Yapılacaklar

- [ ] iOS Build (EAS)
- [ ] App Store yayını
- [ ] Widget desteği
- [ ] Çoklu dil desteği (i18n)

## Lisans

MIT License

## İletişim

GitHub: [@hasancanyildizz](https://github.com/hasancanyildizz)
