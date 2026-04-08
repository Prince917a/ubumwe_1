<template>
  <div>
    <h1>SignUp For Free</h1>

    <form>
      <div>
        <label>Name:</label><br>
        <input type="text" v-model="name" />
      </div>

      <div>
        <label>Email:</label><br>
        <input type="email" v-model="email" />
      </div>

      <div>
        <label>Password:</label><br>
        <input type="password" v-model="password" />
      </div>

      <br>
      <button type="submit">SignUp Now</button>
    </form>


  </div>
</template>



<style>
h1 {
  text-align: center;
}

form {
  width: 300px;
  margin: auto;
}

input {
  width: 100%;
  padding: 5px;
  margin-top: 5px;
  border-radius:5px;
}

button {
  padding: 8px;
}
</style>