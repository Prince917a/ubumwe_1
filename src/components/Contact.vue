<template>
  <div class="contact">
    <h1>Contact Us</h1>

    <div class="card">
      <p><strong>Email:</strong> info@ubumwehotel.com</p>
      <p><strong>Phone:</strong> +250 788 630 959</p>
      <p><strong>Location:</strong> Rubavu, Gisenyi</p>
    </div>
  </div>
</template>

<style scoped>
.contact {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 60vh;
  padding: 20px;
  background-color: #f8fafc;
  font-family: 'Inter', system-ui, sans-serif;
}

h1 {
  color: #1e293b;
  font-size: 2.5rem;
  font-weight: 800;
  margin-bottom: 30px;
  letter-spacing: -0.025em;
}

.card {
  background: white;
  padding: 40px;
  border-radius: 24px;
  box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.05), 0 10px 10px -5px rgba(0, 0, 0, 0.02);
  width: 100%;
  max-width: 450px;
  border: 1px solid #f1f5f9;
}

p {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 0;
  border-bottom: 1px solid #f1f5f9;
  color: #64748b;
  font-size: 1.1rem;
}

p:last-child {
  border-bottom: none;
}

strong {
  color: #334155;
  font-weight: 600;
  text-transform: uppercase;
  font-size: 0.85rem;
  letter-spacing: 0.05em;
}




</style>