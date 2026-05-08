<template>
  <div class="signup-page">
    <h1>SignUp For Free</h1>

    <form @submit.prevent="handleSubmit">
      <div class="form-group">
        <label>Name:</label>
        <input type="text" v-model="name" />
      </div>

      <div class="form-group">
        <label>Email:</label>
        <input type="email" v-model="email" />
      </div>

      <div class="form-group">
        <label>Password:</label>
        <input type="password" v-model="password" />
      </div>

      <button type="submit">SignUp Now</button>
    </form>
  </div>
</template>

<style scoped>
.signup-page {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 40px 20px;
  font-family: sans-serif;
}

h1 {
  color: #2c3e50;
  margin-bottom: 20px;
}

form {
  background-color: #ffffff;
  padding: 30px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  width: 100%;
  max-width: 380px;
}

.form-group {
  width: 100%;
  margin-bottom: 15px;
}

label {
  display: block;
  font-weight: 600;
  margin-bottom: 5px;
  color: #333;
}

input {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  box-sizing: border-box;
}

input:focus {
  outline: none;
  border-color: #42b983;
}

button {
  width: 100%;
  padding: 12px;
  background-color: #42b983;
  color: white;
  border: none;
  border-radius: 5px;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
  margin-top: 10px;
}

button:hover {
  background-color: #3aa876;
}
</style>