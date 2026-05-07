<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Normativa

    .mt-5.pt-4
      .fullwidth-bg.fullwidth-bg--1
      img(data-aos="fade-up")(src="@/assets/curso/tema4/1.png", alt="").z-2
      
      .row.justify-content-center.z-2.mb-3
        .col-lg-10.p-4.drop-shadow(data-aos="fade-down")
          div.banner-text.shadow
            p.mb-0 La industria hotelera cuenta con un conjunto de normas que regulan la actividad del servicio de alojamiento. Conocerlas y aplicarlas es indispensable para prestar un servicio eficiente y evitar situaciones que puedan generar sanciones o perjuicios al establecimiento.
            p.mb-0 Para el procedimiento de registro (check-in) se debe considerar la Norma Técnica Sectorial Hotelera NTSH 003, que establece los requisitos de competencia laboral para el cargo de recepcionista de establecimiento de alojamiento y hospedaje. En el material complementario se encuentra el enlace para ampliar la información sobre esta norma.


</template>

<script>
export default {
  name: 'Tema4',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
