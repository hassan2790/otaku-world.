<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Hexa Anime News</title>
  <meta name="description" content="Hexa Anime News - Sab se tez aur naye anime updates har roz! Watch reels, upload content, and stay updated.">
  <meta name="keywords" content="Anime News, Hexa, Anime Reels, One Piece, Demon Slayer, Naruto, Manga, Anime Uploads">
  <meta name="author" content="Hassan Irfan">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Segoe UI', sans-serif; }
    body { background-color: #fff0f8; color: #333; }
    header { background-color: #cc3399; color: white; padding: 20px; text-align: center; }
    nav { background-color: #ff66b2; display: flex; justify-content: center; flex-wrap: wrap; }
    nav a { padding: 12px 20px; color: white; text-decoration: none; font-weight: bold; }
    nav a:hover { background-color: #e60073; }
    .hero { padding: 40px; text-align: center; background: #ffd6e7; }
    .hero h1 { font-size: 2.5rem; margin-bottom: 10px; }
    .hero p { font-size: 1.2rem; }
    .section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    .news-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .card { background: white; padding: 20px; border-radius: 10px; box-shadow: 0 0 10px #ccc; }
    .card img { width: 100%; border-radius: 10px; }
    footer { background-color: #cc3399; color: white; text-align: center; padding: 20px; margin-top: 40px; }
    input[type="text"], input[type="file"], textarea {
      width: 100%; padding: 10px; margin-top: 10px;
      border-radius: 5px; border: 1px solid #ccc;
    }
    button { padding: 10px 20px; border: none; background: #cc3399; color: white; border-radius: 5px; cursor: pointer; }
    button:hover { background: #b30074; }
    .chatbot {
      position: fixed; bottom: 10px; right: 10px;
      background: #fff; border-radius: 15px;
      box-shadow: 0 0 10px #aaa;
      width: 300px; max-height: 400px;
      overflow: hidden; display: flex; flex-direction: column;
    }
    .chat-header { background: #cc3399; color: white; padding: 10px; font-weight: bold; text-align: center; }
    .chat-messages { flex: 1; padding: 10px; overflow-y: auto; font-size: 14px; }
    .chat-input { display: flex; padding: 10px; border-top: 1px solid #ddd; }
    .chat-input input { flex: 1; padding: 5px; }
    .chat-input button { background: #cc3399; color: white; border: none; padding: 5px 10px; }
    @media screen and (max-width: 500px) {
      .chatbot { width: 90%; }
    }
  </style>
</head>
<body>

<header>
  <h1>Hexa Anime News</h1>
  <p>Sab se tez aur naye anime updates yahan miltay hain!</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#news">News</a>
  <a href="#reels">Reels</a>
  <a href="#upload">Upload</a>
  <a href="#contact">Contact</a>
  <a href="#hosting">Hosting</a>
  <a href="#domain">Domain</a>
  <a href="#seo">SEO</a>
</nav>

<section class="hero" id="home">
  <h1>Welcome to Hexa!</h1>
  <p>Yahan mile ga aapko har anime ka asli update — har roz!</p>
</section>

<section class="section" id="news">
  <h2>📰 Aaj ki News</h2>
  <div class="news-grid">
    <div class="card">
      <img src="https://i.imgur.com/Z3g6qWb.jpeg" alt="Anime Image">
      <h3>Demon Slayer Season 4 Announced!</h3>
      <p>Naya arc is saal ke end tak a raha hai! Fans excited! 🔥</p>
    </div>
    <div class="card">
      <img src="https://i.imgur.com/g9tE1Qp.jpg" alt="Anime Image">
      <h3>One Piece Gear 5 Episode Release</h3>
      <p>Episode 1071 ne internet tor diya! Trending no.1!</p>
    </div>
  </div>
</section>

<section class="section" id="reels">
  <h2>🎥 Anime Reels</h>
  <video src="reels/sample.mp4" width="100%" controls></video>
</section>

<section class="section" id="upload">
  <h2>📤 Apna Content Upload Karain</h2>
  <form onsubmit="event.preventDefault(); alert('File uploaded (demo)!');">
    <input type="text" placeholder="Aap ka Naam" required />
    <input type="file" required />
    <button type="submit">Upload</button>
  </form>
</section>

<section class="section" id="contact">
  <h2>📩 Rabta Karain</h2>
  <form>
    <input type="text" placeholder="Aap ka Naam" required />
    <input type="text" placeholder="Email" required />
    <textarea placeholder="Message likhain..." rows="4"></textarea>
    <button type="submit">Send</button>
  </form>
</section>

<section class="section" id="hosting">
  <h2>🌐 Hosting Info</h2>
  <p>Yeh site static hosting pe banai gayi hai (Netlify, GitHub Pages). Aap isay .zip file upload kar ke public bana saktay hain.</p>
</section>

<section class="section" id="domain">
  <h2>🔗 Domain Setup</h2>
  <p>Sample Domain: <strong>https://hexa-anime-news.netlify.app</strong></p>
  <p>Custom domain connect karna ho to aap DNS settings ka use kar ke apna domain connect kar saktay hain (e.g. Namecheap, GoDaddy).</p>
</section>

<section class="section" id="seo">
  <h2>🔍 SEO Ready</h2>
  <p>Website mein SEO meta tags already added hain. Google isay 1-2 hafton mein crawl kar lay ga.</p>
</section>

<footer>
  <p>&copy; 2025 Hexa Anime News | Powered by Hassan Irfan</p>
</footer>

<div class="chatbot">
  <div class="chat-header">💬 Hexa Bot</div>
  <div class="chat-messages" id="messages">
    <div><strong>Bot:</strong> Salam! Kis anime ke baare mein poochhna hai?</div>
  </div>
  <div class="chat-input">
    <input type="text" id="userInput" placeholder="Type message..." />
    <button onclick="sendMessage()">Send</button>
  </div>
</div>

<script>
  function sendMessage() {
    const input = document.getElementById('userInput');
    const msgBox = document.getElementById('messages');
    const msg = input.value.trim();
    if (msg === '') return;
    msgBox.innerHTML += `<div><strong>You:</strong> ${msg}</div>`;
    setTimeout(() => {
      msgBox.innerHTML += `<div><strong>Bot:</strong> Mujhe is baare mein zyada maloomat nahi, lekin check kar ke bataun ga! 😊</div>`;
      msgBox.scrollTop = msgBox.scrollHeight;
    }, 600);
    input.value = '';
  }
</script>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Hexa Anime News</title>
  <meta name="description" content="Hexa Anime News - Sab se tez aur naye anime updates har roz! Watch reels, upload content, and stay updated.">
  <meta name="keywords" content="Anime News, Hexa, Anime Reels, One Piece, Demon Slayer, Naruto, Manga, Anime Uploads">
  <meta name="author" content="Hassan Irfan">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Segoe UI', sans-serif; }
    body { background-color: #fff0f8; color: #333; }
    header { background-color: #cc3399; color: white; padding: 20px; text-align: center; }
    nav { background-color: #ff66b2; display: flex; justify-content: center; flex-wrap: wrap; }
    nav a { padding: 12px 20px; color: white; text-decoration: none; font-weight: bold; }
    nav a:hover { background-color: #e60073; }
    .hero { padding: 40px; text-align: center; background: #ffd6e7; }
    .hero h1 { font-size: 2.5rem; margin-bottom: 10px; }
    .hero p { font-size: 1.2rem; }
    .section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    .news-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .card { background: white; padding: 20px; border-radius: 10px; box-shadow: 0 0 10px #ccc; }
    .card img { width: 100%; border-radius: 10px; }
    footer { background-color: #cc3399; color: white; text-align: center; padding: 20px; margin-top: 40px; }
    input[type="text"], input[type="file"], textarea {
      width: 100%; padding: 10px; margin-top: 10px;
      border-radius: 5px; border: 1px solid #ccc;
    }
    button { padding: 10px 20px; border: none; background: #cc3399; color: white; border-radius: 5px; cursor: pointer; }
    button:hover { background: #b30074; }
    .chatbot {
      position: fixed; bottom: 10px; right: 10px;
      background: #fff; border-radius: 15px;
      box-shadow: 0 0 10px #aaa;
      width: 300px; max-height: 400px;
      overflow: hidden; display: flex; flex-direction: column;
    }
    .chat-header { background: #cc3399; color: white; padding: 10px; font-weight: bold; text-align: center; }
    .chat-messages { flex: 1; padding: 10px; overflow-y: auto; font-size: 14px; }
    .chat-input { display: flex; padding: 10px; border-top: 1px solid #ddd; }
    .chat-input input { flex: 1; padding: 5px; }
    .chat-input button { background: #cc3399; color: white; border: none; padding: 5px 10px; }
    @media screen and (max-width: 500px) {
      .chatbot { width: 90%; }
    }
  </style>
</head>
<body>

<header>
  <h1>Hexa Anime News</h1>
  <p>Sab se tez aur naye anime updates yahan miltay hain!</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#news">News</a>
  <a href="#reels">Reels</a>
  <a href="#upload">Upload</a>
  <a href="#contact">Contact</a>
  <a href="#hosting">Hosting</a>
  <a href="#domain">Domain</a>
  <a href="#seo">SEO</a>
</nav>

<section class="hero" id="home">
  <h1>Welcome to Hexa!</h1>
  <p>Yahan mile ga aapko har anime ka asli update — har roz!</p>
</section>

<section class="section" id="news">
  <h2>📰 Aaj ki News</h2>
  <div class="news-grid">
    <div class="card">
      <img src="https://i.imgur.com/Z3g6qWb.jpeg" alt="Anime Image">
      <h3>Demon Slayer Season 4 Announced!</h3>
      <p>Naya arc is saal ke end tak a raha hai! Fans excited! 🔥</p>
    </div>
    <div class="card">
      <img src="https://i.imgur.com/g9tE1Qp.jpg" alt="Anime Image">
      <h3>One Piece Gear 5 Episode Release</h3>
      <p>Episode 1071 ne internet tor diya! Trending no.1!</p>
    </div>
  </div>
</section>

<section class="section" id="reels">
  <h2>🎥 Anime Reels</h>
  <video src="reels/sample.mp4" width="100%" controls></video>
</section>

<section class="section" id="upload">
  <h2>📤 Apna Content Upload Karain</h2>
  <form onsubmit="event.preventDefault(); alert('File uploaded (demo)!');">
    <input type="text" placeholder="Aap ka Naam" required />
    <input type="file" required />
    <button type="submit">Upload</button>
  </form>
</section>

<section class="section" id="contact">
  <h2>📩 Rabta Karain</h2>
  <form>
    <input type="text" placeholder="Aap ka Naam" required />
    <input type="text" placeholder="Email" required />
    <textarea placeholder="Message likhain..." rows="4"></textarea>
    <button type="submit">Send</button>
  </form>
</section>

<section class="section" id="hosting">
  <h2>🌐 Hosting Info</h2>
  <p>Yeh site static hosting pe banai gayi hai (Netlify, GitHub Pages). Aap isay .zip file upload kar ke public bana saktay hain.</p>
</section>

<section class="section" id="domain">
  <h2>🔗 Domain Setup</h2>
  <p>Sample Domain: <strong>https://hexa-anime-news.netlify.app</strong></p>
  <p>Custom domain connect karna ho to aap DNS settings ka use kar ke apna domain connect kar saktay hain (e.g. Namecheap, GoDaddy).</p>
</section>

<section class="section" id="seo">
  <h2>🔍 SEO Ready</h2>
  <p>Website mein SEO meta tags already added hain. Google isay 1-2 hafton mein crawl kar lay ga.</p>
</section>

<footer>
  <p>&copy; 2025 Hexa Anime News | Powered by Hassan Irfan</p>
</footer>

<div class="chatbot">
  <div class="chat-header">💬 Hexa Bot</div>
  <div class="chat-messages" id="messages">
    <div><strong>Bot:</strong> Salam! Kis anime ke baare mein poochhna hai?</div>
  </div>
  <div class="chat-input">
    <input type="text" id="userInput" placeholder="Type message..." />
    <button onclick="sendMessage()">Send</button>
  </div>
</div>

<script>
  function sendMessage() {
    const input = document.getElementById('userInput');
    const msgBox = document.getElementById('messages');
    const msg = input.value.trim();
    if (msg === '') return;
    msgBox.innerHTML += `<div><strong>You:</strong> ${msg}</div>`;
    setTimeout(() => {
      msgBox.innerHTML += `<div><strong>Bot:</strong> Mujhe is baare mein zyada maloomat nahi, lekin check kar ke bataun ga! 😊</div>`;
      msgBox.scrollTop = msgBox.scrollHeight;
    }, 600);
    input.value = '';
  }
</script>

</body>
</html>
