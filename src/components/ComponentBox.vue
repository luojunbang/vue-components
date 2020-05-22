<template>
  <div class="box">
    <div class="content">
      <slot />
    </div>
    <h3>Name</h3>
    <p>Details</p>
  </div>
</template>
<script>
export default {
  name: 'ComponentBox',
};
</script>

<style lang="scss" scoped>
.box {
  width: 440px;
  background-color: white;
  box-shadow: 0px 20px 60px -10px rgba(68, 53, 106, 0.08);
  padding: 20px;
  border-radius: 20px;
  .content {
    width: 400px;
    height: 400px;
    margin-bottom: 20px;
    background-color: white;
  }
  h3 {
    margin-bottom: 10px;
    font-weight: 400;
    font-size: 18px;
  }
}
</style>
