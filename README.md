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

## 🧰 Screenshots


**Main Page: Trending Movies/ Latest Movies:**

<img width="300" height="1000" alt="Screenshot_20250917-121118 MovieS" src="https://github.com/user-attachments/assets/2f7a6bc3-7a15-4da3-aafa-4ab2344b4c10" />
<img width="300" height="1000" alt="Screenshot_20250917-121507 MovieS" src="https://github.com/user-attachments/assets/758667bb-8cb5-4ad3-8c57-314b7c4d68e8" />


**Search Page:**

<img width="300" height="1000" alt="Screenshot_20250917-121639 MovieS" src="https://github.com/user-attachments/assets/eb88f506-de78-4def-a54b-437075b6a5a9" />


**Skeleton Loading:**

<img width="300" height="1000" alt="Screenshot_20250917-121703 MovieS" src="https://github.com/user-attachments/assets/b8672247-ad3a-42fb-ad38-d599ad7b2fea" />


**Search Results:**

<img width="300" height="1000" alt="Screenshot_20250917-122023 MovieS" src="https://github.com/user-attachments/assets/45d0edcb-edaf-443d-8af3-94b6cf66a69f" /> <img width="300" height="1000" alt="Screenshot_20250917-121856 MovieS" src="https://github.com/user-attachments/assets/38c1102c-af64-4dc1-a213-aaf812af0737" /> <img width="300" height="1000" alt="Screenshot_20250917-122813 MovieS" src="https://github.com/user-attachments/assets/52d16ffc-e394-481d-944c-3e0e6cf7b0a1" />


**Movie Details :**

<img width="300" height="1000" alt="Screenshot_20250917-122422 MovieS" src="https://github.com/user-attachments/assets/a2802407-bfa0-4104-9d9b-8c07b6fca137" />
<img width="300" height="1000" alt="Screenshot_20250917-122429 MovieS" src="https://github.com/user-attachments/assets/cb99535b-cd5c-42fb-a114-852813e6af61" />


**Available on:**

<img width="300" height="1000" alt="Screenshot_20250917-123003 MovieS" src="https://github.com/user-attachments/assets/cded22bc-21e8-4987-8519-75ec3e01aa22" />


**Profile Page:**

<img width="300" height="1000" alt="Screenshot_20250917-122554 MovieS" src="https://github.com/user-attachments/assets/8f3fb00d-2706-494c-99f9-0d67ae9bd536" />

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
