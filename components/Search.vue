<template lang="pug">
  input.search(placeholder="Search (does not work currently, sorry)")
</template>

<style lang="scss">
input {
  padding: 0.5rem 1.5rem 0.5rem 1.5rem;
  border-radius: 0.3rem;
  background: #eee;
  font-size: 12px;

  &:focus {
    outline: none;
  }
}
</style>
