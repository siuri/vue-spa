<template>
  <nav class="navbar has-shadow">
    <div class="container">
      <router-link to="/category/front-end" exact>
        <img src="http://bit.ly/vue-img" alt="Vue SPA"/>
      </router-link>
      <router-link class="navbar-item is-tab" to="/category/front-end">Front-End</router-link>
      <router-link class="navbar-item is-tab" :to="{ name: 'category', params: { id: 'mobile'}}">Mobile</router-link>
      <router-link class="navbar-item is-tab" to="/login">Login</router-link>
    </div>
  </nav>
</template>
