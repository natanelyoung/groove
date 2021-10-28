<template>
  <div>
    <div class="navbar w-clearfix">
      <nuxt-link to="/" class="logo w-inline-block">
        <img src="@/assets/Groove-beta-logo.svg" loading="lazy" alt=""></nuxt-link>
      <div class="nav-menu">
        <div class="close-wrap">
          <a toggleclass=".nav-menu,open" href="#" class="close w-inline-block"><img src="@/assets/close.svg" loading="lazy" alt="" class="image-5"></a>
        </div>
        <nuxt-link to="/" class="nav-link home">Groove</nuxt-link>
        <nuxt-link to="/community" class="nav-link">Community</nuxt-link>
        <nuxt-link to="/#join" class="nav-link">Join our beta</nuxt-link>
        <a href="https://medium.com/groove-with-us" target="_blank" class="nav-link">Blog</a>
      </div>
      <a toggleclass=".nav-menu,open" href="#" class="burger w-inline-block"><img src="@/assets/menu.svg" loading="lazy" alt=""></a>
    </div>
    <div class="small-navbar w-clearfix">
      <nuxt-link to="/" class="logo w-inline-block"><img src="@/assets/Groove-beta-logo.svg" loading="lazy" alt=""></nuxt-link>
      <div class="nav-menu open">
        <nuxt-link to="/community" class="nav-link">Community</nuxt-link>
        <a href="https://medium.com/groove-with-us" target="_blank" class="nav-link">Blog</a>
        <div class="nav-btn-wrap">
          <nuxt-link to="/#join" class="btn nav w-inline-block">
            <p class="btn-txt">Get early access<br></p>
            <div class="arrow">
              <div class="arrow-line"></div>
              <div class="arrow-triangle"></div>
            </div>
          </nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>
