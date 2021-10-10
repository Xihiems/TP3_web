<template>
  <Button>
    <slot></slot>
  </Button>
</template>

<script>
export default {
  name: "BaseButton"
}
</script>

<style scoped>
button{
  padding :0.5em;
  background-color: azure;
  color:black;
  margin: 0.25em 0.5em;

}
</style>