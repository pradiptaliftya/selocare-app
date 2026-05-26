# SeloCare - Perlindungan Drainase & Prediksi Banjir Pintar

Aplikasi mobile smart city untuk monitoring drainase dan prediksi banjir berbasis AI.

## Fitur Utama

- 🎯 **Dashboard Realtime** - Pantau kondisi drainase kota secara langsung
- 🤖 **AI Flood Prediction** - Prediksi banjir menggunakan machine learning
- 🚀 **Smart Drain Monitoring** - Monitor sensor air, sampah, dan aliran realtime
- 🗺️ **Peta Interaktif** - Lihat lokasi rawan banjir dan rute evakuasi
- 📢 **Notifikasi Pintar** - Alert banjir dan peringatan cuaca ekstrem
- 📱 **Laporan Warga** - Kirim laporan dengan foto dan GPS otomatis
- 🆘 **Emergency Center** - Akses nomor darurat dan SOS 1 klik
- 👥 **Community Awareness** - Edukasi dan berbagi informasi banjir

## Tech Stack

- **Frontend**: React + TypeScript + Tailwind CSS
- **State Management**: Zustand
- **Animation**: Framer Motion
- **Maps**: Leaflet + React Leaflet
- **Charts**: Chart.js
- **Backend**: Firebase
- **Build**: Vite

## Setup

```bash
# Install dependencies
npm install

# Development
npm run dev

# Build
npm run build

# Preview
npm run preview
```

## Struktur Project

```
src/
├── components/
│   ├── layout/
│   ├── cards/
│   ├── modals/
│   └── common/
├── pages/
│   ├── SplashScreen.tsx
│   ├── Home.tsx
│   ├── Monitoring.tsx
│   ├── Prediction.tsx
│   ├── Maps.tsx
│   ├── Notifications.tsx
│   ├── Reports.tsx
│   └── Emergency.tsx
├── hooks/
├── store/
├── types/
├── utils/
└── App.tsx
```

## License

MIT
