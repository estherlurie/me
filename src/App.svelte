<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import heart from '/heart.svg'
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <div class="header">
    <h1 class="name">esti</h1>
    <img class="logo" src={heart}/>
  </div>
  <div class="links">
    <a class="link" href="https://www.github.com/estherlurie">developer</a>
    <a class="link" href="https://www.instagram.com/bedrumorsband">bass player</a>
    <a class="link">language learner</a>
    <a class="link" href="https://www.twitter.com/rustologist">tweeter</a>
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

    .link {
        display: block;
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
