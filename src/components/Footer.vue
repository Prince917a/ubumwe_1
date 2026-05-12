<template>
  <footer class="footer">
    <h3>Ubumwe Hotel</h3>

    <div class="footer-contact">
      <p>Email: 
        <a href="mailto:info@ubumwehotel.com">info@ubumwehotel.com</a>
      </p>

      <p>Phone: 
        <a href="tel:+250788000000">+250 788 000 000</a>
      </p>
    </div>

    <div class="socials">
      <a href="https://facebook.com" target="_blank">Facebook</a>
      <a href="https://twitter.com" target="_blank">Twitter</a>
      <a href="https://linkedin.com" target="_blank">LinkedIn</a>
    </div>

    <p class="copy">© 2026 Ubumwe Hotel</p>
  </footer>
</template>

<style>
.footer {
  background: #222;
  color: white;
  text-align: center;
  padding: 40px 20px;
}

.footer-contact {
  margin: 15px 0;
}

.footer a {
  color: #00bcd4;
  text-decoration: none;
  transition: color 0.3s;
}

.footer a:hover {
  text-decoration: underline;
  color: #00e5ff;
}

.socials {
  margin: 20px 0;
  display: flex;
  justify-content: center;
  gap: 15px;
  flex-wrap: wrap;
}

.copy {
  margin-top: 20px;
  font-size: 14px;
  opacity: 0.7;
}

@media screen and (max-width: 768px) {
  .footer {
    padding: 30px 15px;
  }

  .footer-contact p {
    margin: 10px 0;
    font-size: 15px;
  }

  .socials {
    gap: 20px;
  }
}

@media screen and (max-width: 480px) {
  .footer h3 {
    font-size: 1.2rem;
  }

  .footer-contact p {
    display: flex;
    flex-direction: column;
    gap: 5px;
  }

  .socials {
    flex-direction: column;
    gap: 10px;
  }

  .socials a {
    background: rgba(255, 255, 255, 0.05);
    padding: 10px;
    border-radius: 8px;
  }
}
</style>