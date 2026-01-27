# 🎬 Movie Search App (Vite + React + TypeScript)

A fast, modern movie search web app built with **Vite**, **React**, and **TypeScript**, powered by the [OMDb API](https://www.omdbapi.com/).  
Search for movies, view key details, and explore film info in a clean, responsive UI.

---

## ✨ Features

- 🔍 **Instant movie search** by title
- 📄 **Movie details**: poster, year, genre, plot summary, ratings (where available)
- 💾 **Client-side state** for remembering your latest results in the current session
- ⚡ **Vite dev server** for ultra-fast development and hot reloads
- 📱 **Responsive design** – works on desktop, tablet, and mobile
- 🧹 **Type-safe codebase** using TypeScript for better DX and maintainability

---

## 🧱 Tech Stack

- **Frontend:** React 18 + TypeScript
- **Bundler/Dev Server:** Vite
- **Styling:** CSS (or add Tailwind/your preferred framework)
- **API:** OMDb REST API
- **Package Manager:** npm / yarn / pnpm (use what you prefer)

---

## 🚀 Getting Started

### 1. Clone the repository


git clone https://github.com/AyushGokani/movie-search-app-vite.git
cd movie-search-app-vite
2. Install dependencies
# choose one
npm install
# or
yarn install
# or
pnpm install
3. Configure environment variables
This project uses the OMDb API.
Create a .env file in the project root (same level as package.json) and add:

VITE_OMDB_API_KEY=your_omdb_api_key_here
You can get a free API key from the OMDb website.

4. Run the development server
npm run dev
# or
yarn dev
# or
pnpm dev
Then open the URL shown in your terminal (usually http://localhost:5173).

5. Build for production
npm run build
# or
yarn build
# or
pnpm build
To preview the production build locally:

npm run preview
📁 Project Structure
This is the typical structure – adjust if your repo differs.

movie-search-app-vite/
├─ public/               # Static assets
├─ src/
│  ├─ components/        # Reusable UI components
│  ├─ pages/             # Page-level components (search page, detail view, etc.)
│  ├─ hooks/             # Custom React hooks (if any)
│  ├─ types/             # TypeScript types & interfaces
│  ├─ api/               # API helper functions for OMDb
│  ├─ App.tsx            # Root application component
│  └─ main.tsx           # React entry point
├─ index.html
├─ vite.config.ts
├─ tsconfig.json
└─ package.json
🔧 Possible Improvements / Next Steps
Some ideas for extending the app:

⭐ Favourites / Watchlist stored in localStorage

📊 More detailed stats (IMDb rating, runtime, cast, etc.)

🌙 Dark mode toggle

🌍 Filtering by year, type (movie/series), or genre

🧪 Unit tests with Vitest / React Testing Library

🌐 Deployment to Netlify, Vercel, or GitHub Pages

🤝 Contributing
Suggestions, issues, and pull requests are welcome.
Feel free to fork the repo and open a PR if you’d like to improve the UI, add features, or refactor the code.
