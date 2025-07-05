import React from "react";
import "./main.css";
import "./responsive.css";

function App() {
  return (
    <div className="app">
      <header className="header">
        <h1>Otaku World 🗞️</h1>
        <p>Anime ki har taza khabar, ab Roman Urdu mein!</p>
      </header>

      <main className="news-section">
        <div className="news-card">
          <h2>One Piece ka New Episode Released!</h2>
          <p>Luffy ka gear 5 action fans ko pagal kar gaya 🔥</p>
        </div>
        <div className="news-card">
          <h2>Demon Slayer Final Arc Confirmed</h2>
          <p>2025 mein final season release hone wala hai. Taiyaar ho jao!</p>
        </div>
      </main>

      <footer className="footer">
        <p>&copy; 2025 Otaku World - Sab haq mehfooz</p>
      </footer>
    </div>
  );
}

export default App;
