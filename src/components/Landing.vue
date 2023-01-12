<template>
  <div class="landing">
    <h2>Noaspot</h2>
    <h1>Coming Soon</h1>
    <p>Add your email below to </p>
    <p>be notified when we launch.</p>
    <p id="copyright">© 2023 Noaspot LLC</p>
  </div>
</template>

<script>
export default {
  name: 'Landing',
}
</script>

<style scoped>
.landing {
  color: #FFF;
}

h2 {
  letter-spacing: 2px;
}

h1 {
  font-size: 5em;
  font-weight: 900;
}

p {
  margin: 5px;
  font-weight: 600;
}

#copyright {
  font-size: 0.85em;
  font-weight: 400;
}
</style>
