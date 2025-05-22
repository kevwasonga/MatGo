# 🚐 MatGo - Nairobi’s Dopest Matatu Simulator

**MatGo** is a vibrant, mobile-first React Native app that gamifies the chaotic, colorful, and iconic *matatu* culture of Kenya. From blasting gengetone to racing through Githurai, MatGo lets users customize, drive, and experience the realest public transport system on the African continent — *digitally*.

## 🎯 What’s This App About?

MatGo is more than a game. It’s a cultural experience. Players take on the role of a **matatu driver (dere)** and can:

- 🎨 **Customize** their matatu with graffiti, lights, speakers, slogans, and names like *"Jesus is Lord"* or *"Nganya Supreme"*
- 🛣️ **Select routes** (e.g., Umoja → CBD) based on real-world Nairobi map logic
- 🧑‍✈️ **Race or cruise**—compete against other matatus or simulate an everyday route with jams and kamageras
- 🎧 **Play music** from a built-in playlist (local hits, gengetone, gospel, reggae)
- 💾 **Drive offline** so even users in shags can vibe

---

## 🛠️ Tech Stack

| Feature | Stack |
|--------|-------|
| App Framework | `React Native (Expo)` |
| Animation | `react-native-reanimated`, `Lottie`, `react-native-animatable` |
| Maps & Routing | `react-native-maps`, custom JSON route data |
| State & Navigation | `React Navigation`, `Zustand` |
| Backend (planned) | Firebase / Supabase / Local JSON storage |
| Music & Assets | Local storage + optional Spotify/YouTube integrations |

---

## 📁 Project Structure

```bash
MatGo/
├── assets/               # Lottie files, icons, audio, matatu art
├── components/           # Reusable UI components (MatatuCard, RouteSelector, etc.)
├── screens/              # Main app screens (Home, Garage, RaceTrack, etc.)
├── data/                 # Routes, matatu models, cultural facts
├── hooks/                # Custom React hooks
├── navigation/           # Stack & tab navigation config
├── App.tsx               # Root app component
└── README.md
