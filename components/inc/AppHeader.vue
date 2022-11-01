<template>
  <div class="sticky-top">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark shadow">
  <div class="container">
    <a class="navbar-brand white" href="#">
      <img src="../../static/images/logo dev.png" class="logo-img">
      </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <NuxtLink class="nav-link active" aria-current="page" to="/">Home</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink class="nav-link" to="/About">About Us</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink class="nav-link" to="/contact">Contact</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink class="nav-link" to="/Services">Services</NuxtLink>
        </li>

      </ul>

    </div>
  </div>
</nav>
  </div>
</template>

<script>
export default {
  name: 'AppHeader'
}
</script>

<style>
.logo-img{
  height: 70px;

  border-radius: 20%;
}
</style>
