<template>
  <div>
    <h1>test</h1>
    <p>A vue project.</p>
    <button type="button" @click="btnClick" value="点击我">sdsdsd</button>
  </div>
</template>

<script>
  export default {
    name: 'app',
    methods: {
      btnClick() {
        alert('click');
      }
    }
  };
</script>
