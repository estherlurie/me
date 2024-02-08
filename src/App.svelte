<script lang="ts">
  import heart from "/heart.svg";
  import NewTabLink from "./lib/NewTabLink.svelte";
</script>

<main>
  <div class="header">
    <h1 class="name">esti</h1>
    <img class="logo" alt="I <3 you!" src={heart} />
  </div>
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
    display: flex;
  }

  .name {
    color: #db3030;
  }

  .links {
    font-size: 1.25em;
  }

  .logo {
    width: 50px;
    margin-left: 10px;
  }

  @media (prefers-color-theme: light) {
    .name {
      color: #ff6060;
    }
  }
</style>
