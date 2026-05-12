<template>
  <div class="app">
    <nav class="navbar">
      <h2 class="logo">Ubumwe Hotel</h2>
      <div class="links">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/contact">Contact</router-link>
        <router-link to="/registiration" class="btn">Sign Up</router-link>
      </div>
    </nav>

    <main class="content">
      <router-view />
    </main>

    <footer class="footer">
      <h3>Ubumwe Hotel</h3>
      <p>Email: 
        <a href="mailto:info@ubumwehotel@gmail.com">info@ubumwehotel@gmail.com</a>
      </p>
      <p>Phone: 
        <a href="tel:+250788630959">+250 788 630 959</a>
      </p>
      <div class="socials">
        <a href="https://facebook.com" target="_blank">Facebook</a>
        <a href="https://twitter.com" target="_blank">Twitter</a>
        <a href="https://linkedin.com" target="_blank">LinkedIn</a>
      </div>
      <p class="copy">© 2026 Ubumwe Hotel</p>
    </footer>
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

.app {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  background: #f4f7fb;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 5%;
  background: linear-gradient(135deg, #1e3c72, #2a5298);
  color: white;
  flex-wrap: wrap;
}

.links {
  display: flex;
  align-items: center;
}

.links a {
  margin-left: 20px;
  text-decoration: none;
  color: white;
  transition: 0.3s;
}

.links a:hover {
  opacity: 0.7;
  text-decoration: underline;
}

.btn {
  padding: 8px 18px;
  border-radius: 20px;
  background: #00d4ff;
  color: #111 !important;
  font-weight: bold;
}

.content {
  flex: 1;
  padding: 40px 5%;
}

.footer {
  text-align: center;
  padding: 30px 5%;
  background: #111;
  color: #ccc;
}

.footer a {
  color: #00d4ff;
  text-decoration: none;
}

.socials {
  margin: 15px 0;
}

.socials a {
  margin: 0 10px;
  color: #ccc;
}

@media (max-width: 768px) {
  .navbar {
    flex-direction: column;
    text-align: center;
  }

  .logo {
    margin-bottom: 15px;
  }

  .links {
    flex-direction: column;
    width: 100%;
  }

  .links a {
    margin: 10px 0;
  }

  .content {
    padding: 20px;
  }
}
</style>