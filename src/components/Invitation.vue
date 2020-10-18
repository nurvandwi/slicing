<template>
  <div class="bg-couple">
    <div class="container ">
      <div class="">
        <ul class=" d-flex justify-content-around mt-2 mt-lg-0">
          <li class="nav-item active">
            <a class="nav-link text-white" href="#">Akad Nikah</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Resepsi Pernikahan</a>
          </li>
        </ul>
      </div>
      <div class="d-flex justify-content-center margin-custom text-white">
        <h1 class="">Me and you just us Two</h1>
      </div>
      <div class="d-flex justify-content-center margin-custom text-white">
        <h5 class="">19.12.2020</h5>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Parisienne&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Montserrat&display=swap");
h1 {
  font-family: "Parisienne", cursive;
  font-size: 4em;
}

h5,
a {
  font-family: "Montserrat", sans-serif;
  font-size: 1em;
}

.image-adjust img {
  height: 6rem;
}

ul li {
  list-style: none;
  text-transform: uppercase;
}

.margin-custom {
  margin-top: 50vh;
}

.bg-couple {
  width: 100%;
  height: auto;
  background: url("../assets/invitation.png") no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;

  opacity: 0.65;
}
</style>