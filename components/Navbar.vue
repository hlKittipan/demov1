<template>
  <div class="header sticky">
    <h2 class="logo">
      Website
    </h2>
    <input id="chk" type="checkbox">
    <label for="chk" class="show-menu-btn">
      <span><font-awesome-icon :icon="['fas', 'ellipsis-h']" class="text-warning" /></span>
    </label>
    <ul class="menu">
      <a href="#">Home</a>
      <a href="#">Register</a>
      <a href="#">Login</a>
      <a href="#">Promotion</a>
      <a href="#">Contact us</a>
      <label for="chk" class="hide-menu-btn">
        <span><font-awesome-icon :icon="['fas', 'times']" class="text-warning" /></span>
      </label>
    </ul>
  </div>
</template>
