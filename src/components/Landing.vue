<template>
  <div class="landing">
    <div class="header">
      <h2>Noaspot</h2>
    </div>
    <div class="content">
      <h1>Coming Soon</h1>
      <p>Come back soon to download our iOS app</p>
      <p>or send us an
      <a href="mailto:support@noaspot.com">email</a>
      for more information.</p>
    </div>
    <div class="footer">
      <p id="copyright">© 2023 Noaspot LLC</p>
    </div>
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

.header {
  height: 10%;
}

.content {
  width: 100%;
  position: fixed;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}

a {
  color: #111;;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

.footer {
  position: fixed;
  bottom: 0;
  left: 0;
  margin-bottom: 20px;
  width: 100%;
  text-align: center;
}

h2 {
  letter-spacing: 2px;
}

h1 {
  font-size: 3em;
  font-weight: 900;
  margin: 0;
}

p {
  margin: 10px;
  font-weight: 600;
}

#copyright {
  font-size: 0.85em;
  font-weight: 500;
}

@media only screen and (min-width: 600px) {
  h1 {
    font-size: 5em;
  }
}
</style>
