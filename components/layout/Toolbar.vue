<template>
  <VToolbar
    clipped-left
    app
    fixed
    :color="toolbarColor"
  >
    <VBtn icon @click.stop="drawer = !drawer">
      <VIcon :color="elementsColor">
        mdi-chevron-left
      </VIcon>
    </VBtn>

    <VSpacer />

    <img
      src="../../static/logos/logo-azul.svg"
      alt="Tigre Performance"
      width="auto"
      height="90%"
    >

    <VSpacer />

    <VBtn icon @click.stop="drawer = !drawer">
      <VIcon :color="elementsColor">
        mdi-menu
      </VIcon>
    </VBtn>
  </VToolbar>
</template>

<script>
export default {
  props: {
    toolbarColor: { type: String, default: 'white' },
    elementsColor: { type: String, default: 'primary' } // ,
    // imageName: { type: String, default: 'logo-azul' }
  }
}
</script>
