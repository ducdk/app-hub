<template>
  <div class="boxed_wrapper ltr">
    <Header />
    <Nuxt />
  </div>
</template>

<script>
import Header from '../components/layouts/Header.vue';

export default {
    name: "DefaultLayout",
    components: { Header }
}
</script>
