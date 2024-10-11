<template>

  <main-nav />
  <div class="mt-5">
    5frfcrdwfcdfe
    <ins class="adsbygoogle"
             style="display:block"
             data-ad-client="ca-pub-0000000000000000" 
             data-ad-slot="1234567890"               
             data-ad-format="auto"></ins>
  </div>
  <router-view />
</template>

<script>
import MainNav from "@/components/Navigation/MainNav.vue";

export default {
  name: "App",
  components: { MainNav },
    mounted() {
    if (typeof window.adsbygoogle !== 'undefined') {
      window.adsbygoogle = window.adsbygoogle || [];
      window.adsbygoogle.push({});
    }
  }
};
</script>
