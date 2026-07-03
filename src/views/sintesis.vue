<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    p.mb-4 El proceso de escalado es el último paso del patronaje; entendiendo los cuadros de tallas se realiza el análisis detallado de las prendas y se definen las medidas específicas para cada talla, cada empresa tiene su propio cuadro de tallas, pero el proceso de escalado, sea digital o manual, siempre es el mismo. En el siguiente diagrama se presentan los temas más significativos tratados dentro de este componente: 

    .row.justify-content-center.mb-5
      .col-lg-9
        figure
          img(src="@/assets/curso/sintesis.svg", alt="Mapa conceptual que ilustra el proceso de escalado digital, desglosándolo en escalado manual de prendas y escalado en Optitex.")
    .row.justify-content-center
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
