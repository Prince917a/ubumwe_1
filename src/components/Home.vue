<template>
  <div class="home">
    <h1>Welcome to Ubumwe Hotel</h1>
    <p>Murakaza neza muri hotel nziza.</p>
  </div>
  <img src="@/assets/ubumwe.jpg" alt="Ubumwe Hotel" class="hotel-photo" />
</template>

<style scoped>
.home {
  text-align: center;
  padding: 60px 20px 30px;
  background: linear-gradient(to bottom, #ffffff, #f8fafc);
  font-family: 'Poppins', system-ui, sans-serif;
}

h1 {
  color: #0f172a;
  font-weight: 800;
  margin-bottom: 7px;
  font-size: 2.5rem;
}

p {
  color: #64748b;
  max-width: 600px;
  margin: 0 auto;
  font-size: 1.1rem;
}

.hotel-photo {
  display: block;
  width: 90%;
  max-width: 1000px;
  height: 450px;
  object-fit: cover;
  border-radius: 30px;
  margin: 20px auto;
  transition: transform 0.3s ease;
}

.hotel-photo:hover {
  transform: scale(1.02);
}

@media screen and (max-width: 1024px) {
  h1 {
    font-size: 2.2rem;
  }
  
  .hotel-photo {
    height: 350px;
  }
}

@media screen and (max-width: 768px) {
  .home {
    padding: 40px 15px 20px;
  }

  h1 {
    font-size: 1.8rem;
  }

  p {
    font-size: 1rem;
  }

  .hotel-photo {
    height: 280px;
    border-radius: 20px;
    width: 95%;
  }
}

@media screen and (max-width: 480px) {
  h1 {
    font-size: 1.5rem;
  }

  .hotel-photo {
    height: 220px;
    border-radius: 15px;
  }
}
</style>