<template>
  <div class="wrapper">
    <div class="columns">
      <div class="column">
        <div class="control">
          <h1 class="title">Epic todos</h1>
        </div>
      </div>
    </div>

    <div class="columns">
      <div class="column">
        <div class="control">
          <input class="input" type="text" placeholder="Что нужно сделать?">
        </div>
      </div>
    </div>
    <div class="columns">
      <div class="column">
        <div class="control">
          <input class="input" type="text" placeholder="Что нужно сделать?">
        </div>
      </div>
    </div>

    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          <strong>Bulma</strong> by
          <a href="https://jgthms.com">Jeremy Thomas</a>. The source code is licensed
          <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The website content
          is licensed
          <a
            href="http://creativecommons.org/licenses/by-nc-sa/4.0/"
          >CC BY NC SA 4.0</a>.
        </p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "app"
};
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
