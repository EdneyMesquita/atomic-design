<template>
  <div class="services">
    <Service
      title="Front-end"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptas, recusandae laborum. Corrupti asperiores laboriosam sed consequatur similique debitis qui provident officia! Recusandae exercitationem harum laboriosam, corrupti possimus repellat quis eligendi."
    />

    <Service
      title="Back-end"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptas, recusandae laborum. Corrupti asperiores laboriosam sed consequatur similique debitis qui provident officia! Recusandae exercitationem harum laboriosam, corrupti possimus repellat quis eligendi."
    />

    <Service
      title="Devops"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptas, recusandae laborum. Corrupti asperiores laboriosam sed consequatur similique debitis qui provident officia! Recusandae exercitationem harum laboriosam, corrupti possimus repellat quis eligendi."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: {
    Service
  }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
