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
}

p {
  
  color: #64748b;
  max-width: 600px;
  margin: 0 auto;
  
}

.hotel-photo {
  display: block;
  width: 90%;
  max-width: 1000px;
  height: 300px;
  border-radius: 30px;
  margin: 0 auto;
}

.hotel-photo:hover {
  transform: scale(1.02);
}



</style>