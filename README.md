# MovieS
Movie discovery app built with **React Native** and **Expo**, powered by the [TMDB API](https://www.themoviedb.org/documentation/api).  
It lets users search for movies, explore detailed information, view top cast, and even see where to stream them — all within a smooth and responsive UI.

---
- 🔍 **Search for Movies**
  - Smart search with debounced input and real-time results using TMDB’s search endpoint.
- 🎬 **Detailed Movie Info**
  - Beautifully designed detail screen with:
    - Poster, title, release year, and runtime
    - Tagline and overview
    - Spoken languages and genres
    - Budget and revenue
    - Production companies
- ⭐ **Ratings & Votes**
  - Average rating, vote count, and adult flags
- 🧑‍🎤 **Top Cast Section**
  - Horizontally scrollable cast cards with image and character name
- 📺 **Watch Providers**
  - Shows logos of streaming platforms (like Netflix, Prime Video, etc.) where the movie is available to stream
- 🖼️ **Custom Splash Screen**
  - App logo + intro branding on app load
- 💀 **Skeleton Loaders**
  - Lightweight custom-built placeholders (no third-party)
- 📊 **Search Analytics**
  - Optional integration with Appwrite to track popular searches

## 🧰 Built With

- **React Native (Expo)**
- **TypeScript**
- **TMDB API**
- **Appwrite** (optional for analytics)
- **NativeWind (Tailwind CSS for RN)**
- **React Navigation**
- **EAS (Expo Application Services)**

---
## 🛣️ Roadmap

- [x] Add movie search functionality with debounced input
- [x] Display movie details with genre, budget, revenue, etc.
- [x] Show top cast with images and character names
- [x] Show watch providers (streaming platforms)
- [x] Add splash screen (like Instagram with branding)
- [x] Add custom skeleton loaders (no third-party)
- [x] Responsive dark theme UI
- [ ] Integrate trailer playback (YouTube / TMDB videos)
- [ ] Add favorites / watchlist functionality
- [ ] User authentication (email + social login)
- [ ] Implement infinite scroll / pagination
- [ ] Multilingual support (i18n)
- [ ] Offline support with caching
- [ ] Push notifications for upcoming movies
- [ ] Deploy web version (via Expo web or Next.js)
