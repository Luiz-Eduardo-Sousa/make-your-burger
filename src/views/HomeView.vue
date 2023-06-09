<template>
  <Banner />
  <div class="main-container">
    <h1>HOME</h1>
  <BugerForm />
</div>
</template>

<script>
import Banner from '@/components/Banner.vue';
import BugerForm from '@/components/BugerForm.vue';


export default {
  name: "Home",
  components: {
    Banner,
    BugerForm
}
}

</script>
