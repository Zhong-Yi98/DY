<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <keep-alive>
    <router-view/>

    </keep-alive>
  </div>
</template>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
}
</style>
