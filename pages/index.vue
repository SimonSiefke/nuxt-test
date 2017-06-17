<template>
  <div>
    <div class="content">
      <h1>Hello, !</h1>
      <p>
        This is a super simple example of how to use <a href="https://github.com/nuxt/nuxt.js" target="_blank">Nuxt.js</a> and <a href="https://auth0.com" target="_blank">Auth0</a> together.
      </p>
      <p >
        You're not authenticated yet. Maybe you want to <nuxt-link to="/auth/sign-in" class="link">sign in</nuxt-link> and see what happens?
      </p>
      <p>
        Now that you're authenticated, maybe you should try going to our <nuxt-link to="/secret" class="link">super secret page</nuxt-link>!
      </p>
    </div>
  </div>
</template>

<script>

  
</script>

<style scoped>
.content {
  max-width: 750px;
  margin: 0 auto;
  text-align: center;
}
</style>
