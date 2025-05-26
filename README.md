# Movie Search App 🎬

A modern React web application to search for movies, view trending titles, and discover details using the TMDB API. Built with Vite, Tailwind CSS, and Appwrite for tracking trending searches.

## Features

- 🔍 **Search Movies:** Instantly search for movies using the TMDB API.
- 📈 **Trending Section:** See the most popular searches powered by Appwrite.
- 🎨 **Responsive UI:** Clean, mobile-friendly design with Tailwind CSS.
- ⚡ **Fast & Modern:** Built with React and Vite, optimized for performance.
- 🗂️ **Debounced Search:** Reduces unnecessary API calls for a smoother experience.

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/movies_web.git
   cd movies_web
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root with the following (replace with your keys):
   ```
   VITE_TMDB_API_KEY=your_tmdb_api_key
   VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
   VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
   VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   ```

4. **Run the development server:**
   ```sh
   npm run dev
   ```

5. **Build for production:**
   ```sh
   npm run build
   ```

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Appwrite](https://appwrite.io/)
- [TMDB API](https://www.themoviedb.org/documentation/api)

## Project Structure

```
src/
  components/      # Reusable React components
  assets/          # Static assets
  App.jsx          # Main app component
  appwrite.js      # Appwrite integration
  main.jsx         # Entry point
  index.css        # Tailwind and global styles
public/
  ...              # Static images and icons
```

## License

MIT

---

**GitHub Description:**  
A modern React app to search and discover movies, featuring trending searches powered by Appwrite and a responsive UI with Tailwind CSS. Built with Vite and integrates the TMDB API.
