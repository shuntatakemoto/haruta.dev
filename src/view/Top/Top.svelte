<style>
main {
  text-align: center;
}
.link-list {
  list-style: none;
  font-size: x-large;
  font-family: 'Comic Sans MS', 'Marker Felt';
}
</style>

<script>
import { link } from 'svelte-spa-router';
import { routesNav } from '../../constants/index';
import ProfileImage from '../../components/ProfileImage.svelte';
</script>

<ProfileImage />
<main>
  <div class="link-list">
    {#each routesNav as route}
      <p key="{route.name}">
        {#if route.route}
          <a href="{route.path}" use:link>
            {route.name}
          </a>
        {:else}
          <a href="{route.path}">
            {route.name}
          </a>
        {/if}
      </p>
    {/each}
  </div>
</main>
