<style>
.container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
</style>

<script>
import Router from "svelte-spa-router";
import { routes } from "./routes/index.js";
import Header from "./components/Header.svelte";
import Footer from "./components/Footer.svelte";
</script>

<main class="container">
  <Header />
  <Router routes="{routes}" />
  <Footer />
</main>
