<template>
  <div class="col-full" :class="$style.centered">
    <h1 :class="$style.headingLarge">Not Found</h1>
    <p class="text-large" :class="$style.textLarge">Ooops, we couldn't find what you are looking for. Why don't you</p>
    <router-link :to="{ name: 'Home' }">
      go home instead?
    </router-link>
  </div>
</template>

<script>
export default {
}
</script>

<style module>
  .headingLarge {
    font-size: 70px;
  }
  .textLarge {
    font-size: 30px;
    font-weight: 100;
  }
  .centered {
      text-align: center;
  }
</style>