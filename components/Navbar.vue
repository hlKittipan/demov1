<template>
  <div class="header sticky" on="handleScroll">
    <h3 class="logo">
      Website
    </h3>
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

<script>
export default {
  data() {
    return {
      limitPosition: 500,
      scrolled: false,
      lastPosition: 0
    }
  },
  methods: {
    handleScroll() {
      if (this.lastPosition < window.scrollY && this.limitPosition < window.scrollY) {
        this.scrolled = true;
        // move up!
      } 
      
      if (this.lastPosition > window.scrollY) {
        this.scrolled = false;
        // move down
      }
      
      this.lastPosition = window.scrollY;
      // this.scrolled = window.scrollY > 250;
    }
  },
  created() {
    window.addEventListener("scroll", this.handleScroll);
  }
}
</script>