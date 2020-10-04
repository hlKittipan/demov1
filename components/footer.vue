<template>
  <div class="footer">
    <div class="footer-container">
      <div class="left-col">
        <span class="footer-logo">Website</span>
        <div class="social-media">
          <a
            href="#"
          ><font-awesome-icon
            :icon="['fab', 'facebook-f']"
            class="text-warning"
          /></a>
          <a
            href="#"
          ><font-awesome-icon
            :icon="['fab', 'twitter']"
            class="text-warning"
          /></a>
          <a
            href="#"
          ><font-awesome-icon
            :icon="['fab', 'instagram']"
            class="text-warning"
          /></a>
          <a
            href="#"
          ><font-awesome-icon
            :icon="['fab', 'youtube']"
            class="text-warning"
          /></a>
          <a
            href="#"
          ><font-awesome-icon
            :icon="['fab', 'linkedin-in']"
            class="text-warning"
          /></a>
        </div>
        <p class="rights-text">
          © 2020 website
        </p>
      </div>
      <div class="right-col">
        <h1>Our Newsletter</h1>
        <div class="border" />
        <p>Enter your e-mail to get our news</p>
        <form action="" class="newslatter-form">
          <input type="text" class="txtb" placeholder="Enter your email">
          <b-button type="button" class="footer-btn" variant="outline-warning">
            Submit
          </b-button>
        </form>
      </div>
    </div>
  </div>
</template>
