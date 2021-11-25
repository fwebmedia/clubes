<template>
  <div>
      <div class="bg-azul py-2">
      </div>
      <picture>
          <source srcset="../assets/images/banner-mobile.png" media="(max-width:767px;)">
          <img src="../assets/images/banner.png" alt="Fybeca" class="image">
      </picture>
      <div class="bg-azul px-3 pt-5 pb-5 has-text-white has-text-centered">
          <div class="columns">
              <div class="column">
                  <h2 class="title has-text-white">
                      Descubre los beneficios que tenemos para ti
                  </h2>
              </div>
          </div>
      </div>
      <div class="bg-celeste py-5 px-6">
          <div class="container has-text-white">
            <div class="columns">
                <div class="column">
                    <p class="is-flex is-align-items-center">
                        <img src="../assets/images/descuentos.png" alt="Fybeca" class="image pr-3">
                        <span>
                        <strong class="has-text-white">Descuentos</strong> y promociones
                        </span>
                    </p>
                </div>
                <div class="column is-3-desktop">
                    <p class="is-flex is-align-items-center">
                        <img src="../assets/images/productos.png" alt="Fybeca" class="image pr-3">
                        <span>
                        Productos <strong class="has-text-white">GRATIS</strong>
                        </span>
                    </p>
                </div>
                <div class="column is-5-desktop">
                    <p class="is-flex is-align-items-center">
                        <img src="../assets/images/talleres.png" alt="Fybeca" class="image pr-3">
                        <span>
                        Talleres de <strong class="has-text-white">salud, prevención, belleza</strong> y más
                         </span>
                    </p>
                </div>
            </div>
      </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped>
.bg-azul{
    background:#183e63;
}
.bg-celeste{
    background: #008fd6;
}
</style>