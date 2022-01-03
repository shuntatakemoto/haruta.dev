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
import { routesNav, externalNav } from "../../constants/index";
import ProfileImage from "../../components/ProfileImage.svelte";
</script>

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

    {#each externalNav as external}
      <p key="{external.name}">
        <a href="{external.path}">
          {external.name}
        </a>
      </p>
    {/each}
  </div>
</main>
