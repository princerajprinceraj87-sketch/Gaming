# Gaming
For 4K style gaming pic 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gaming Hub</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: white;
    }
    header {
      background: #020617;
      padding: 15px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 { margin: 0; }
    header button {
      padding: 8px 12px;
      cursor: pointer;
      border-radius: 6px;
      border: none;
    }
    .hero {
      text-align: center;
      padding: 50px 20px;
      background: linear-gradient(to right, #0ea5e9, #9333ea);
      font-size: 32px;
      font-weight: bold;
    }
    .games {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .card {
      background: #1e293b;
      border-radius: 12px;
      overflow: hidden;
      transition: 0.3s;
    }
    .card:hover { transform: scale(1.05); }
    .card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }
    .card h3 { text-align: center; }
    .card button {
      display: block;
      margin: 10px auto;
      padding: 8px 12px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      background: #22c55e;
      color: white;
    }
    .login {
      text-align: center;
      padding: 20px;
    }
    .login input {
      padding: 10px;
      margin: 5px;
      border-radius: 6px;
      border: none;
    }
    .chat {
      position: fixed;
      bottom: 10px;
      right: 10px;
      width: 250px;
      background: #1e293b;
      border-radius: 10px;
      padding: 10px;
    }
    .chat input {
      width: 100%;
      padding: 5px;
    }
    footer {
      text-align: center;
      padding: 10px;
      background: #020617;
    }
  </style>
</head>
<body>

<header>
  <h1>🎮 Gaming Hub</h1>
  <button onclick="toggleMode()">Toggle Mode</button>
</header>

<div class="hero">Welcome Gamer 🚀</div>

<div class="login">
  <h2>Login</h2>
  <input type="text" placeholder="Username">
  <input type="password" placeholder="Password">
  <button onclick="alert('Logged in!')">Login</button>
</div>

<section class="games">
  <div class="card">
    <img src="https://images.unsplash.com/photo-1605902711622-cfb43c44367f">
    <h3>Action Game</h3>
    <button onclick="alert('Downloading...')">Download</button>
  </div>
  <div class="card">
    <img src="https://images.unsplash.com/photo-1598550476439-6847785fcea6">
    <h3>Racing Game</h3>
    <button onclick="alert('Downloading...')">Download</button>
  </div>
  <div class="card">
    <img src="https://images.unsplash.com/photo-1511512578047-dfb367046420">
    <h3>Shooting Game</h3>
    <button onclick="alert('Downloading...')">Download</button>
  </div>
</section>

<div class="chat">
  <h4>💬 Chat</h4>
  <input type="text" placeholder="Type message...">
</div>

<footer>
  © 2026 Gaming Hub
</footer>

<script>
function toggleMode() {
  document.body.style.background = document.body.style.background === 'white' ? '#0f172a' : 'white';
  document.body.style.color = document.body.style.color === 'black' ? 'white' : 'black';
}
</script>

</body>
</html>![12260](https://github.com/user-attachments/assets/235e7aa9-3ca4-4021-a66f-bbd3781578bc)
![12259](https://github.com/user-attachments/assets/0ae36f94-3cbc-4d6e-b055-0ef13f09e207)
