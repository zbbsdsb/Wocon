# Wocon
the end of tinder :3
# 🌍 Wocon - Find Your Next Travel Story

**Fill your journeys with surprise and create lasting memories with like-minded travel companions.**

---

## 📖 Introduction

Wocon is an innovative travel social app designed to solve the pain points of solo travelers: "traveling alone can be lonely, and finding reliable companions is difficult and often unsafe." With a clean interface and a smart matching algorithm, we help you find ideal travel buddies who want to visit the same place at the same time.

*   **Surprise:** Encounter interesting souls from around the world, filling your trip with serendipitous joy.
*   **Safety:** Build a trusted community through third-party social verification and a mutual rating system.
*   **Simplicity:** No flashy ads or over-polished hype. Focused on core features for a smooth user experience.

## ✨ Core Features (MVP Stage)

- [x] **Account System** - Email sign-up/login, third-party social account binding
- [x] **Map Exploration** - Search and pin your desired destinations on a map
- [x] **Smart Matching** - Automatically find companions based on destination and timing
- [x] **Real-time Chat** - Communicate safely and seamlessly with your matched partners
- [x] **Reputation Rating** - Mutual post-trip reviews to build community trust

## 🚀 Coming Soon

- [ ] Enhanced Matching Algorithm (based on travel purpose, interest tags)
- [ ] Advanced Safety Features (identity verification, manual review)
- [ ] "Impact Travel" Section for poverty alleviation and education support
- [ ] Multi-language & International Version Support

## 🛠️ Tech Stack

**Frontend:**
- [Expo](https://expo.dev/) (React Native) - Cross-platform mobile development
- [React Navigation](https://reactnavigation.org/) - Routing & Navigation
- [React Native Maps](https://github.com/react-native-maps/react-native-maps) - Map Component

**Backend & Data:**
- [Supabase](https://supabase.com/) - Backend-as-a-Service (BaaS), including:
  - PostgreSQL Database
  - User Authentication
  - Real-time Subscriptions (for chat)
  - RESTful API

**Development & Deployment:**
- Git & GitHub - Version Control
- Expo Application Services (EAS) - App Build & Deployment

## 📦 Installation & Setup

Follow these steps to run Wocon on your device:

### Prerequisites
- Node.js (LTS version recommended)
- npm or yarn
- A physical phone or simulator/emulator
- Expo Go app (for testing on a physical device)

### Steps
1.  **Clone the repository**
    ```bash
    git clone https://github.com/your-username/wocon.git
    cd wocon
    ```

2.  **Install dependencies**
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Environment Configuration**
    - Copy the `.env.example` file to `.env`.
    - Obtain your `EXPO_PUBLIC_SUPABASE_URL` and `EXPO_PUBLIC_SUPABASE_ANON_KEY` from your Supabase project settings and fill them in the `.env` file.

4.  **Start the development server**
    ```bash
    npx expo start
    ```
    Scan the QR code that appears in your terminal with the Expo Go app to open the project.

## 🤝 Contributing

We welcome and appreciate all contributions! Whether you're fixing a typo, improving documentation, or building a new feature.

If you are a solo developer interested in this project, feel free to Fork this repository and submit a Pull Request or open an Issue for discussion.

## 📄 License

This project is licensed under the [MIT](LICENSE) License.

## 👨‍💻 Developer

Independently developed and maintained by [CeaserZhao](https://github.com/your-github-username).

---
### Inspiration & Philosophy
> "I hope Wocon's role is not limited to adding fun to our travels; I also hope it can play its own part in poverty alleviation, especially in education."
>
> — CeaserZhao, Oct 26, 2025
