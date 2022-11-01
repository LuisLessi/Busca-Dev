<template>
  <div>

    <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active" data-bs-interval="10000">
      <img src="../static/images/img1.jpg" class="d-block w-100" alt="slider1">
      <div class="carousel-caption d-none d-md-block">
        <h5>Mobile/desktop developer</h5>
        <p>The Desktop Programmer aims to create executable applications on the computer and the mobile apps for smartphones.
</p>
      </div>
    </div>
    <div class="carousel-item" data-bs-interval="2000">
      <img src="../static/images/img2.jpg" class="d-block w-100" alt="slider2">
      <div class="carousel-caption d-none d-md-block">
        <h5>Web developer</h5>
        <p>The Web developer's role is to create programs, code and test systems, sites and portals aimed at the internet environment. Performs system maintenance, making any necessary corrections, in order to meet the needs of users.
</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="../static/images/img3.jpg" class="d-block w-100" alt="slider3">
      <div class="carousel-caption d-none d-md-block">
        <h5>Data Analyst/Developer</h5>
        <p>The professional will be responsible for developing, testing, improving and maintaining new and existing databases, thus enabling users to access data effectively. As part of our IT team, one of your responsibilities will be to work with developers to ensure systems consistency.
</p>

      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>

</div>
</template>

<script>

export default {
  name: 'slider'

  }

</script>

<style>
h5{
  text-decoration-color: black;
}
</style>

