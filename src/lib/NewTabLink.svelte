<script lang="ts">
    export let url: string;
    export let text: string;
</script>

<style>
    .link { 
        display: block;
    }
</style>

<a class="link" target="_blank" rel="noopener noreferrer" href={url}>{text}</a>


