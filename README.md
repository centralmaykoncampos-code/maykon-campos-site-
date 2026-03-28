index.html
style.css
script.js
banner.jpg
arte.jpg
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #000;
  color: white;
  text-align: center;
}

.banner {
  width: 100%;
  max-height: 500px;
  object-fit: cover;
}

nav {
  background: #111;
  padding: 15px;
}

nav a {
  color: gold;
  margin: 15px;
  text-decoration: none;
  font-weight: bold;
}

section {
  padding: 60px 20px;
}

.foto {
  width: 220px;
  border-radius: 50%;
  margin: 20px 0;
}

footer {
  background: #000;
  padding: 20px;
}

/* animação */
.fade {
  opacity: 0;
  transform: translateY(20px);
  transition: 1s;
}

.fade.visible {
  opacity: 1;
  transform: translateY(0);
}

/* botão whatsapp */
.whatsapp-float {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #25D366;
  color: white;
  font-size: 28px;
  padding: 15px;
  border-radius: 50%;
  text-decoration: none;
}
