<template>
  <div class="container">
    <div>
      <h1 class="title">
        首页
      </h1>
    </div>
  </div>
</template>

<script>

import Logo from '~/components/Logo.vue'
export default {
  components: {
    Logo
  }
}
</script>

<style lang="scss">
.container {
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: red;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
  &:hover{
    color: red;
  }
}


</style>
