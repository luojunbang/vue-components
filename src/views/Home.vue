<template>
  <div class="container">
    <ComponentBox>
      <div class="flexrow height100">
        <VerificationCode />
      </div>
    </ComponentBox>
  </div>
</template>

<script>
// @ is an alias to /src
import ComponentBox from '@/components/ComponentBox';
import VerificationCode from '@/components/VerificationCode/VerificationCode.vue';
export default {
  name: 'Home',
  components: {
    ComponentBox,
    VerificationCode
  },
};
</script>

<style lang="scss" scoped>
.container {
  background-color: #efefef;
  width: 100%;
  padding: 30px;
}
</style>
