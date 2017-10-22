<template>
    <div class="card">
      <div class="card-content">
        <slot name="title"></slot>
        <slot name="content"></slot>
      </div>
      <footer class="card-footer">
        <a :href="link" target="_blank" class="card-footer-item">Read More</a>
      </footer>
    </div>
</template>
<script>
  export default {
    props: ['link']
  }
</script>
