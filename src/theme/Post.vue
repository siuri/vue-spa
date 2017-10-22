<template>
    <div class="card">
      <div class="card-content">
        <h3>{{ post.title }}</h3> {{post.content}}
      </div>
      <footer class="card-footer">
        <a :href="post.link" target="_blank" class="card-footer-item">Read More</a>
      </footer>
    </div>
</template>
<script>
  export default {
    props: ['post']
  }
</script>
