<template>
  <div>
    <AppBar></AppBar>
    <Nuxt />
    <Footer></Footer>
  </div>
</template>
<script>
import AppBar from "~/components/core/AppBar";
import Footer from "~/components/core/Footer";
export default {
  components: {
    AppBar,
    Footer
  }
}
</script>
