<script lang="ts">
  import heart from "/heart.svg";
  import NewTabLink from "./lib/NewTabLink.svelte";
</script>

<main>
  <div class="header">
    <h1 class="name">esti lurie</h1>
    <h2 class="name">/ɛsti lɜri/</h2>
  </div>
  <br />
  <div class="links">
    <NewTabLink url={"https://www.github.com/estherlurie"} text={"developer"} />
    <NewTabLink
      url={"https://www.instagram.com/bedrumorsband"}
      text={"bass player"}
    />
    <NewTabLink
      url={"https://youtu.be/EM8my7_ApbA?si=sFcY1HKag6tlya-k"}
      text={"language learner"}
    />
    <NewTabLink url={"https://www.twitter.com/rustologist"} text={"tweeter"} />
  </div>
</main>

<style>
  .header {
    display: block;
  }

  .name {
    color: #db3030;
    margin: 0;
  }

  .links {
    font-size: 1.25em;
  }

  @media (prefers-color-theme: light) {
    .name {
      color: #ff6060;
    }
  }
</style>
