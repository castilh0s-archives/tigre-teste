<template>
  <VApp>
    <Toolbar />

    <VContent>
      <VContainer grid-list-md>
        <nuxt />
      </VContainer>
    </VContent>
  </VApp>
</template>

<script>
import Toolbar from '@/components/layout/Toolbar'
export default {
  components: { Toolbar }
}
</script>
