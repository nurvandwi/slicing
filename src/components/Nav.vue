<template>
  <div class="bg-couple">
    <div class=" ">
      <nav class="navbar navbar-expand-sm py-5">
        <a class="navbar-brand" href="#"
          ><img src="../assets/Group 3.png" alt="" srcset=""
        /></a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav  m-auto">
            <li class="nav-item active">
              <a class="nav-link text-white" href="#">Overview </a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="#">Features</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="#">Technology</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="#">Contact</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="#">Sign Up</a>
            </li>
          </ul>
          <form class="form-inline my-2 d-flex justify-content-between">
            <div class="d-flex justify-content-around">
              <img src="../assets/Frame 1.png" class="" alt="" srcset="" />
              <div class="nav-item dropdown my-2">
                <a
                  class="nav-link text-white dropdown-toggle"
                  href="#"
                  id="navbarDropdown"
                  role="button"
                  data-toggle="dropdown"
                  aria-haspopup="true"
                  aria-expanded="false"
                >
                  EN
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <a class="dropdown-item" href="#">ID</a>
                  <a class="dropdown-item" href="#">Another action</a>
                  <div class="dropdown-divider"></div>
                  <a class="dropdown-item" href="#">Something else here</a>
                </div>
              </div>
              <button
                class=" btn btn-outline-white text-white my-1"
                style="width: 9vw; height: 5vh;"
                type="submit"
              >
                Login
              </button>
            </div>
          </form>
        </div>
      </nav>
      <div class=" text-center margin-custom text-white">
        <h1 class="">CLOUDBUDGET</h1>
        <h5 class="font-24 py-5">
          Cloud budget management for everyone. Only <br />
          €69.95 a Month After a 7 Day Trial of <br />Up to €4.99
        </h5>
        <button class="btn btn-light btn-sign-up rounded">Sign Up</button>
      </div>
      <div
        class="d-flex justify-content-center margin-text-custom text-white"
      ></div>
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
  font-family: "Montserrat", sans-serif;
  font-size: 4em;
}

.btn-outline-white {
  border-color: #ffff;
  color: #ffff;
}

.btn-sign-up {
  color: red;
  width: 10rem;
  height: 50px;
}

.font-24 {
  font-weight: 600;
  font-size: 24px;
  line-height: 150%;
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
  margin-top: 20vh;
}

.bg-couple {
  width: 100%;
  height: 100vh;
  background: url("../assets/Bg.png") no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
</style>