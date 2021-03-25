<template>
  <Container class="home-template">
    <Header />

    <Presentation />

    <Services />
  </Container>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Header, Presentation, Services } from '@/components/organisms'
import { Container } from '@/components/bosons'

export default defineComponent({
  components: {
    Header,
    Presentation,
    Services,
    Container
  }
})
</script>

<style lang="scss" scoped>
.home-template {
  margin: 2rem auto 5rem;
  display: grid;
  grid-gap: 5rem;
}
</style>
