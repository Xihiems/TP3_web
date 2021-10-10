<template>
<div class="home">
  <p>Bienvenue sur notre site !</p>
  <BaseButton>Button</BaseButton>
</div>
</template>

<script>

import BaseButton from "../../Button/BaseButton";
export default {

  name: "HomePage",
  components :{
    BaseButton
  }
}
</script>

<style scoped>
.home{
  position: absolute;
  top: 45%;
  justify-content: center;
  left:45%;

}
</style>