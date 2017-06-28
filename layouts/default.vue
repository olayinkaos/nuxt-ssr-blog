<template>
  <div>
    <!-- navigation -->
    <nav class="nav has-shadow">
      <div class="container">
        <div class="nav-left">
          <nuxt-link to="/" class="nav-item">
            Awesome JS SSR Blog!
          </nuxt-link>
          <nuxt-link active-class="is-active" to="/" class="nav-item is-tab" exact>Home</nuxt-link>
          <nuxt-link active-class="is-active" to="/about" class="nav-item is-tab" exact>About</nuxt-link>
        </div>
      </div>
    </nav>
    <!-- /navigation -->

    <!-- displays the page component -->
    <nuxt/>

  </div>
</template>

<style>
  .main-content {
    margin: 30px 0;
  }
</style>
