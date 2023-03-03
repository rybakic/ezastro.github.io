<script>
  import "./style.css";
  import Header from "../components/header.svelte";
  import Footer from "../components/footer.svelte";
</script>

<div class="">
  <Header />
  <div class="section relative">
    <slot />
    <Footer />
  </div>
</div>

<style>
</style>
