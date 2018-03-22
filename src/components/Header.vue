<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
  
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavDropdown">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <router-link to="/" class="navbar-brand" activeClass="active">Stock Trader</router-link>
      </li>
      <li class="nav-item">
        <router-link to="/portfolio" class="nav-link" activeClass="active">Portfolio</router-link>
      </li>
      <li class="nav-item">
        <router-link to="/stocks" class="nav-link" activeClass="active">Stocks</router-link>
      </li>
      <li class="nav-item">
        <a class="nav-link" activeClass="active" href="#">End Day</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Save & Load
        </a>
        <div class="dropdown-menu " aria-labelledby="navbarDropdownMenuLink">
          <a class="dropdown-item" href="#">Save Data</a>
          <a class="dropdown-item" href="#">Load Data</a>
        </div>
      </li>
    </ul>
  </div>
</nav>
</template>