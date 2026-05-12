<template>
  <div class="about">
    <h1>About Ubumwe Hotel</h1>
    <p>We are here to give you a good services</p>
    
    <div class="image-wrapper">
      <img src="@/assets/jim.jpg" alt="Manager Jim" class="about-img" />  
      <img src="@/assets/service.jpg" alt="Our Services" class="about-service" />
    </div>
  </div>
</template>

<style>
.about {
  text-align: center;
  padding: 40px;
}

.image-wrapper {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin-top: 30px;
}

.about-img, .about-service {
  width: 40%;
  height: 350px;
  object-fit: cover;
  border-radius: 14px;
}

@media screen and (max-width: 1024px) {
  .about-img, .about-service {
    width: 45%;
    height: 300px;
  }
}

@media screen and (max-width: 768px) {
  .about {
    padding: 20px;
  }
  
  .image-wrapper {
    flex-direction: column;
    align-items: center;
  }

  .about-img, .about-service {
    width: 90%;
    height: 250px;
    margin-bottom: 15px;
  }

  h1 {
    font-size: 1.5rem;
  }
}
</style>