<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Eth DevTools
    </p>
    
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>
