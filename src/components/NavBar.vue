<template>
  <div class="hello">
              <nav class="navbar" role="navigation" aria-label="main navigation">
              <div class="navbar-brand">
                <a class="navbar-item" href="https://bulma.io">
                  
                </a>
      
                <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
                  <span></span>
                  <span></span>
                  <span></span>
                </div>
              </div>
            <div id="navbarExampleTransparentExample" class="navbar-menu">
              <div class="navbar-start">
                <div class="control has-icons-left">
                  <input class="input is-medium" type="email" placeholder="Buscar">
                  
                  <span class="icon is-left">
                    <i class="ion-md-search"></i>
                  </span>
                </div>
              </div>
              <div class="navbar-end">
                <div class="navbar-item has-dropdown is-hoverable">
                  <a class="navbar-link " href="https://bulma.io/documentation/overview/start/">
                    <i class="icon ion-ios-contact contact"></i>
                  </a>
                  <div class="navbar-dropdown is-boxed is-right">
                    <a class="navbar-item" href="https://bulma.io/documentation/overview/start/">
                      Overview
                    </a>
                    <a class="navbar-item" href="https://bulma.io/documentation/modifiers/syntax/">
                      Modifiers
                    </a>
                    <a class="navbar-item" href="https://bulma.io/documentation/columns/basics/">
                      Columns
                    </a>
                    <a class="navbar-item" href="https://bulma.io/documentation/layout/container/">
                      Layout
                    </a>
                    <a class="navbar-item" href="https://bulma.io/documentation/form/general/">
                      Form
                    </a>
                    <hr class="navbar-divider">
                    <a class="navbar-item" href="https://bulma.io/documentation/elements/box/">
                      Elements
                    </a>
                    <a class="navbar-item is-active" href="https://bulma.io/documentation/components/breadcrumb/">
                      Components
                    </a>
                  </div>
                </div>
              </div>
            </div>
            </nav>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
