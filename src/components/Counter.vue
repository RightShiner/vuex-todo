// Counter.vue

<template>
  <div class="cotainer">
    <div class="notification">
      <h1 class="title" align="center">
        {{ count }}
      </h1>
    </div>
  </div>
</template>
<script>


export default {
  data: {
    count: 0
  }
}
</script>