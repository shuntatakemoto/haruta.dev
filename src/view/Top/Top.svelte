<style>
main {
  text-align: center;
}
.link-list {
  list-style: none;
  font-size: x-large;
  font-family: "Comic Sans MS", "Marker Felt";
}
</style>

<script>
import { link } from "svelte-spa-router";
import { routesNav } from "../../constants/index";
import Header from "../../components/Header.svelte";
import Footer from "../../components/Footer.svelte";
import ProfileImage from "../../components/ProfileImage.svelte";
</script>

<Header />
<ProfileImage />
<main>
  <div class="link-list">
    {#each routesNav as route}
      <p key="{route.name}">
        <a href="{route.path}" use:link>
          {route.name}
        </a>
      </p>
    {/each}
    <p><a href="https://github.com/shuntatakemoto">Github</a></p>
    <p><a href="https://twitter.com/haruta_8_">Twitter</a></p>
    <p><a href="https://zenn.dev/shuntatakemoto">Zenn</a></p>
  </div>
</main>
<Footer />
