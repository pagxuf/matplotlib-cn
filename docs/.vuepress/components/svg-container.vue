<template>
  <div class="svg-container">
    <slot></slot>
  </div>
</template>

<style lang="scss">
.svg-container {
  margin: 30px auto;
  text-align: center;
  & > svg {
    max-width: 100%;
  }
}
</style>
