<template>
  <div class="bg-couple">
    <div class="container ">
      <div class="d-flex justify-content-center py-5 image-adjust">
        <img src="../assets/nav-couple.png" alt="" />
      </div>
      <div>
        <ul class=" d-flex justify-content-around mt-2 mt-lg-0">
          <li class="nav-item active">
            <a class="nav-link text-white" href="#"
              >Our Story <span class="sr-only">(current)</span></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Invitation</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Location</a>
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
  background: url("../assets/background-wedding.png") no-repeat center center
    fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
</style>