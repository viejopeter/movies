# 🎬 Movie App

Movie App is a **cutting-edge, responsive web application** built with **React**, designed to deliver a seamless and visually stunning experience for movie enthusiasts.  

Users can effortlessly **browse popular movies**, **search for any title in real-time**, and **manage a personal list of favorite movies**, with favorites safely persisted in the browser's **localStorage** for instant access across sessions.  

This project is a showcase of modern front-end development practices, including:  
- **React Functional Components & Hooks** – leveraging state-of-the-art React patterns for clean, maintainable code  
- **Context API for Global State Management** – efficiently manages favorites across the application  
- **Powerful API Integration with [TMDB](https://www.themoviedb.org/documentation/api)** – fetches real-time, up-to-date movie data, including trending and searchable titles  
- **Responsive & Modern UI/UX** – polished dark theme, smooth hover effects, and adaptive layouts for desktop, tablet, and mobile  
- **Clean, Modular, and Portfolio-Ready Codebase** – demonstrates professional-level structure and scalability  

The **TMDB API integration** is the cornerstone of the app, allowing users to access real-time movie information with lightning-fast performance and providing a realistic, professional-grade demo suitable for any developer portfolio.


---

## ✨ Features

- 🎬 **Popular Movies Page** – Loads trending/popular movies on startup  
- 🔍 **Search Functionality** – Search movies by keyword  
- ⭐ **Favorites System** – Add/remove movies, persist favorites in localStorage  
- 🎨 **Modern UI/UX** – Dark theme, hover effects, smooth animations  
- 📱 **Responsive Design** – Works on desktop, tablet, and mobile  
- ⚡ **Fast & Lightweight** – Optimized React components for performance  

---

## 🖥️ Technologies Used

- **React 18** (Functional Components & Hooks)  
- **React Router** (Navigation)  
- **Context API** (Global state management for favorites)  
- **CSS3** with custom animations (Netflix-inspired dark theme)  
- **TMDB API** (Fetch popular and searched movies)  

---

## 📂 Project Structure

```
movie-app/
│
├── src/
│ ├── components/
│ │ ├── MovieCard.jsx
│ │ └── NavBar.jsx
│ ├── contexts/
│ │ └── MovieContext.jsx
│ ├── pages/
│ │ ├── Home.jsx
│ │ └── Favorites.jsx
│ ├── services/
│ │ └── api.js
│ ├── css/
│ │ ├── App.css
│ │ ├── MovieCard.css
│ │ ├── NavBar.css
│ │ ├── Home.css
│ │ └── Favorites.css
│ └── App.jsx
│
└── README.md
```

---

## ⚙️ Installation

### Requirements
- [Node.js](https://nodejs.org/) (v18+)  
- npm (v9+)  
- TMDB API key (free account)  

### Steps
```bash
# Clone the repository
git clone https://github.com/viejopeter/movies.git
cd movies

# Install dependencies
npm install

# Add your TMDB API key
# Create a .env file in the project root:
# REACT_APP_TMDB_API_KEY=your_api_key_here

# Start the development server
npm start
```

**Access the app:**
The app will run at 👉 http://localhost:3000


## 📝 Usage

Open the Home Page to see popular movies

Use the search bar to find movies by title

Click the ♥ button on a movie to add it to your favorites

Navigate to Favorites Page to see all saved movies

Remove movies from favorites by clicking the same button


## 🌟 Portfolio Notes

This project is ideal for showcasing:

React Skills (Hooks, Context API, Routing)

UI/UX Design Sense (Dark theme, grid layout, hover effects)

API Integration (TMDB search & popular movies)

Clean Codebase (Modular structure, reusable components)


## 🧪 Testing

Currently, no formal tests included, but you can manually test:

Adding/removing favorites

Searching for movies

Responsiveness on multiple devices

## 🛠️ Tech Stack

Frontend: React 18, CSS3

State Management: Context API

Routing: React Router

API: TMDB API

Styling: Custom CSS + responsive grid

## 🤝 Contributing

Contributions are welcome! 🎉
If you’d like to improve Movie App, fork the repo and submit a pull request.

## 📜 License

This project is licensed under the MIT License.
See the LICENSE