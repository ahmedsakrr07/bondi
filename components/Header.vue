<template>
  <div>
    <div class="first"> 
      <b-navbar toggleable="lg" type="dark" >
        <b-navbar-brand href="#">Logo</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav class="ml-auto" style="margin-right: 10%;font-size: 16px;">
            <b-nav-item active to="/">Home</b-nav-item>
            <b-nav-item active to="/about">About</b-nav-item>
            <b-nav-item active href="contact">Contact</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
      <div class="background">
          <div class="landing d-flex justify-content-center align-items-center">
            <div class="text-center text-light" style="margin-bottom: 2%">
              <h1 class="title">{{ title }} </h1>
              <p class="lead">{{ dec }} </p>
            </div>
          </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    title: String,
    dec: String
  }
}
</script>

<style>
.first {
  background-image: url("../assets/background.jpg");
  background-repeat: no-repeat;
  min-height: 68vh;
  background-position: top; 
  background-size: cover;
  background-color: rgba(0, 0, 0, 0.6);
  background-blend-mode: hue;
}
.title{
	font-size: 60px;
    margin-top:17%;
}
.lead {
	font-size: 22px;
    font-weight: 500;
    text-transform: capitalize;
}
.arrow {
  width: 50px;
}
@media screen and (max-width: 768px) {
  .title{
	font-size: 30px;
    margin-top:38%;
}
}
</style>
