<template>
  <div class="app">

  
    <nav class="navbar">
      <h2 class="logo">Ubumwe Hotel</h2>

      <div class="links">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/contact">Contact</router-link>
        <router-link to="/registiration">
          Sign Up
        </router-link>
      </div>
    </nav>

    
    <main class="content">
      <router-view />
    </main>

    
    <footer class="footer">
    
    <h3>Ubumwe Hotel</h3>

    <p>Email: 
      <a href="mailto:niyogisubizoprince02@gmail.com">info@ubumwehotel@gmail.com</a>
    </p>

    <p>Phone: 
      <a href="tel:+250788630959">+250 788 630 959</a>
    </p>

    <div class="socials">
      <a href="https://facebook.com" target="_blank">Facebook</a>
      <a href="https://twitter.com" target="_blank"> Twitter</a>
      <a href="https://linkedin.com" target="_blank"> LinkedIn</a>
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
 
  padding: 15px 40px;
  background: linear-gradient(135deg, #1e3c72, #2a5298);
  color: white;
}





.links a {
  margin: 0 15px;
  text-decoration: none;
  color: white;

}

.links a:hover {
  opacity: 0.7;
  text-decoration:underline;
}


.btn {
  padding: 8px 18px;
  border-radius: 20px;
  background: #00d4ff;
  color: #000 !important;
  font-weight: bold;
}


.content {
  flex: 1;
  padding: 40px;
}


.footer {
  text-align: center;
  padding: 15px;
  background: #111;
  color: #ccc;
}


 
  .navbar {
    flex-direction: column;
  }

  .links {
    margin-top: 10px;
    text-align:right;
  }
  
    
  

</style>