<template>
  <div id="app">
   <nav class="navbar navbar-expand-lg navbar-light">
      <a class="navbar-brand" href="#">Recipe App
        <font-awesome-icon icon="carrot" />
      </a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<style>
@import './assets/styles/custom.css';
@import url('https://fonts.googleapis.com/css?family=Work+Sans&display=swap');
  body{
    background-image:url('../src/assets/images/food-background.jpg');
    background-size: cover;
    background-repeat: no-repeat;
  }
</style>
