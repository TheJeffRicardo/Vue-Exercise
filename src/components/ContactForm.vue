<template>
    <h1>This is the Contact Form</h1>
    <form>
        <label for="">Name:</label>
        <input type="text">
        <label for="">Surname:</label>
        <input type="text">
        <label for="">Email:</label>
        <input type="text">
        <button type="submit">Submit</button>
    </form>
</template>

<script>
export default {
  name: 'contact'
}
</script>

<style>
form{
  display: grid;
  gap: 10px;
}
form input{
  margin: auto;
  width: 40%;
  border: none;
  border-bottom: 3px solid rgba(128, 128, 128, 0.505);
  border-radius: 5px;
  padding: 10px;
}
form button{
  margin: auto;
  height: 150%;
  width: 10%;
  border: 2px solid grey;
  border-radius: 10px;
  background-color: white;
}
form button:hover{
  margin: auto;
  height: 150%;
  width: 10%;
  border: 2px solid white;
  border-radius: 10px;
  background-color: grey;
  color: white;
  transition: 0.5s;
  cursor:pointer
}
</style>