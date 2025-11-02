<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MakeIt – Kreative Ideen & Inspiration</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <img src="images/MakeIt.png" alt="MakeIt Logo" class="logo">
    <nav>
      <ul>
        <li><a href="index.html" class="active">Start</a></li>
        <li><a href="ueber.html">Über MakeIt</a></li>
        <li><a href="diy.html">DIY & 3D-Druck</a></li>
        <li><a href="rezepte.html">Gesunde Gerichte</a></li>
        <li><a href="geschenke.html">Geschenkideen</a></li>
        <li><a href="planer.html">Digitale Planer</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="intro">
      <h1>Willkommen auf <span>MakeIt</span>!</h1>
      <p>Entdecke kreative und praktische Ideen rund um DIY, 3D-Druck, Ernährung und leckere Rezepte. 
      Finde Inspiration für Geschenkideen, digitale Planer, gesunde Gerichte und kreative Projekte, 
      die deinen Alltag schöner machen!</p>
    </section>
  </main>

  <footer>
    <p>© 2025 MakeIt | Kreativität leben</p>
  </footer>
</body>
</html>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Montserrat:wght@300;500&display=swap');

body {
  margin: 0;
  font-family: 'Montserrat', sans-serif;
  background-color: #f8f8f8;
  color: #333;
}

header {
  text-align: center;
  padding: 2rem 1rem;
  background-color: #fff;
  border-bottom: 1px solid #e0e0e0;
}

.logo {
  width: 120px;
  margin-bottom: 1rem;
}

nav ul {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 1rem;
}

nav a {
  text-decoration: none;
  color: #444;
  font-weight: 500;
  transition: color 0.3s;
}

nav a:hover,
nav a.active {
  color: #b27f4f;
}

main {
  max-width: 900px;
  margin: 3rem auto;
  padding: 0 1.5rem;
}

h1 span {
  font-family: 'Playfair Display', serif;
  color: #b27f4f;
}

.intro p {
  font-size: 1.1rem;
  line-height: 1.7;
}

footer {
  text-align: center;
  padding: 2rem;
  background-color: #fff;
  font-size: 0.9rem;
  color: #777;
  border-top: 1px solid #e0e0e0;
}
