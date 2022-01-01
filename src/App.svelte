<style>
main {
  text-align: center;
}

.link-list {
  list-style: none;
  font-size: x-large;
  font-family: "Comic Sans MS", cursive;
}

/* @media (min-width: 640px) {
  main {
    max-width: none;
  }
} */
</style>

<script>
import Header from "./Header.svelte";
import Footer from "./Footer.svelte";
</script>

<Header />
<main>
  <div class="link-list">
    <p><a href="./about">About</a></p>
    <p><a href="https://github.com/shuntatakemoto">Github</a></p>
    <p><a href="https://twitter.com/haruta_8_">Twitter</a></p>
    <p><a href="https://zenn.dev/shuntatakemoto">Zenn</a></p>
  </div>
</main>
<Footer />
