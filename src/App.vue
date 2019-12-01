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
            <a class="nav-link" href="#"> About</a>
          </li>
        </ul>
      </div>
    </nav>
    <br><br>
    <div class="container">
      <div class="row">
        <div class="col-md-4" id="left-section">
          <div class="header">
            <h1>Create a New Recipe</h1>
          </div>
          <br>
          <div class="left-desc">
            <p>Become a contributor to our library of recipes by creating your own.</p>
              <button class="btn btn-info" id="search-btn">Search</button>
          </div>
        </div>
        <div class="col-md-8" id="right-section">
          <div class="header">
            <h1>Search Recipes</h1>
          </div>
          <br>
          <div class="right-desc">
            <p>Search our library of recipes added by our community of contributors.</p>
              <input type="text" id="search-area" placeholder="Search.."> <font-awesome-icon icon="search"/>
                <br><br>
              <button class="btn btn-light">Search</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@import './assets/styles/custom.css';
@import url('https://fonts.googleapis.com/css?family=Work+Sans&display=swap');
@import url('https://fonts.googleapis.com/css?family=Heebo:800&display=swap');
  body{
    background-image:url('../src/assets/images/food-background-04.jpg');
  }
</style>
