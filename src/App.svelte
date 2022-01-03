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
</script>

<main class="container">
  <Router routes="{routes}" />
</main>
