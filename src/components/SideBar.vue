<template>

  <div class="hello hellothere">
    
            <div class="column is-narrow sidebar">
          <div class="sidebar-header">
            <strong>Quantum</strong>
          </div>
          <div class="sidebar-body">
            <div class="item active">
              <a><i class="icon ion-ios-home"></i>Home</a>  
            </div>
            <div class="item">
              <a><i class="icon ion-ios-trending-up"></i>Graficas</a>  
            </div>
            <div class="item">
              <a><i class="icon ion-md-grid"></i>Areas</a>  
            </div>
            <div class="item">
              <a><i class="icon ion-ios-contacts"></i>Gestores</a>  
            </div>
            <div class="item">
              <a><i class="icon ion-ios-business"></i>Empresas</a>  
            </div>
            <div class="item">
              <a><i class="icon ion-md-clipboard"></i>Documentos</a>  
            </div>
            <div class="item">
              <a><i class="icon ion-ios-people"></i>Becarios</a>  
            </div>
          </div>
          <div>
          </div>
        </div>

  </div>
</template>

<script>
export default {
  name: 'SideBar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>