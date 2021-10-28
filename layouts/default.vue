<template>
  <div>
    <Nav />
    <Pop />
    <Nuxt />
    <Footer />
    </div>
</template>

<style>

</style>

<script>
import Nav from "~/components/nav";
import Pop from "~/components/popup";
import Footer from "~/components/footer";

export default {
  components: { Nav, Footer, Pop },
};
</script>
