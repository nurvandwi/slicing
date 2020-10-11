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

  <!-- <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Navbar</a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarTogglerDemo02"
      aria-controls="navbarTogglerDemo02"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
      <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
        <li class="nav-item active">
          <a class="nav-link" href="#"
            >Home <span class="sr-only">(current)</span></a
          >
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item">
          <a
            class="nav-link disabled"
            href="#"
            tabindex="-1"
            aria-disabled="true"
            >Disabled</a
          >
        </li>
      </ul>
      <form class="form-inline my-2 my-lg-0">
        <input
          class="form-control mr-sm-2"
          type="search"
          placeholder="Search"
        />
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">
          Search
        </button>
      </form>
    </div>
  </nav> -->
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