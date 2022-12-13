<template>
    <nav class="navbar navbar-dark bg-dark navbar-expand-lg">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Navbar</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <router-link to="/">Home</router-link> 
              </li>
              <li class="nav-item">
                <router-link to="/about">About</router-link> 
              </li>
              <li class="nav-item">
                <router-link to="/contact">Contact</router-link> 
              </li>
              <li class="nav-item">
                <router-link to="/product">Products</router-link>
              </li>
            </ul>
          </div>
        </div>
      </nav>
</template>

<script>
export default{
    name: 'navbar'
}
</script>

<style>
.navbar{
    margin: auto;
}
.navbar-nav{
   margin: auto;
}
.nav-item{
    padding-right: 10px;
}
.nav-item a{
    color: white;
    text-decoration: none;
    font-weight: bold;
}
nav a.router-link-exact-active {
    color: #42b983;
  }
</style>