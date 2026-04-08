<template>
  <footer class="footer">
    <h3>Ubumwe Hotel</h3>

    <p>Email: 
      <a href="mailto:info@ubumwehotel.com">info@ubumwehotel.com</a>
    </p>

    <p>Phone: 
      <a href="tel:+250788000000">+250 788 000 000</a>
    </p>

    <div class="socials">
      <a href="https://facebook.com" target="_blank">Facebook</a>
      <a href="https://twitter.com" target="_blank">Twitter</a>
      <a href="https://linkedin.com" target="_blank">LinkedIn</a>
    </div>

    <p class="copy">© 2026 Ubumwe Hotel</p>
  </footer>
</template>

<script setup>
</script>

<style>
.footer {
  background: #222;
  color: white;
  text-align: center;
  padding: 20px;
}

.footer a {
  color: #00bcd4;
  text-decoration: none;
}

.footer a:hover {
  text-decoration: underline;
}

.socials {
  margin: 10px 0;
}

.socials a {
  margin: 0 10px;
}

.copy {
  margin-top: 10px;
  font-size: 14px;
}
</style>