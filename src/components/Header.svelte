<style>
.header-link {
  display: flex;
  justify-content: center;
}
.header-title {
  display: flex;
  align-items: center;
  font-size: xx-large;
  font-family: "Comic Sans MS", "Marker Felt";
  text-decoration: none;
}
</style>

<script>
import { link } from "svelte-spa-router";
</script>

<header>
  <a href="/" use:link class="header-link">
    <h1 class="header-title">haruta-8.dev</h1>
  </a>
</header>
