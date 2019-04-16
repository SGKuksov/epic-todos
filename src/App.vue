<template>
  <div class="wrapper">
    <header class="navbar is-spaced" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item logo" href="#">Todos</a>

        <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>
    </header>

    <div class="columns is-centered">
      <div class="column is-narrow">
        <div class="panel">
          <p class="panel-heading">Список дел</p>

          <div class="panel-block">
            <div class="control">
              <input class="input" type="text" placeholder="Что нужно сделать?">
            </div>
            <div>
              <button class="button is-warning">Добавить</button>
            </div>
          </div>

          <p class="panel-tabs">
            <a class="is-active">
              Все
              <span class="tag is-info">3</span>
            </a>
            <a>
              Сделаны
              <span class="tag is-info">2</span>
            </a>
            <a>
              Не сделаны
              <span class="tag is-info">1</span>
            </a>
          </p>
          <label class="panel-block">
            <input type="checkbox" checked>
            <span>Учить HTML</span>
          </label>
          <label class="panel-block">
            <input type="checkbox" checked>
            <span>Учить CCS</span>
          </label>
          <label class="panel-block">
            <input type="checkbox">
            <span>Учить JavaScript</span>
          </label>
        </div>
      </div>

      <div class="column is-narrow">
        <button class="button">
          <span>Отметить все</span>

          <span class="icon has-text-success">
            <i class="fas fa-check-square"></i>
          </span>
        </button>

        <button class="button">
          <span>Снять отметку со всех</span>
        </button>

        <button class="button">
          <span>Удалить все отмеченные</span>

          <span class="icon has-text-danger">
            <i class="fas fa-ban"></i>
          </span>
        </button>
      </div>
    </div>

    <div class="columns is-mobile is-centered">
      <div class="column is-narrow">

      </div>
    </div>

    <footer class="footer">
      <div class="content">
        <p>Epic Skills, 2019</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "app"
};
</script>

<style lang="sass" src="../node_modules/bulma/bulma.sass"></style>
<style lang="scss" src="@/assets/style.scss"></style>

