<script>
    import { Button } from "fluent-svelte";
</script>

<div class="big-f">FireCubeStudios</div>
<div class="small-f">Creating apps</div>
<div class="buttons">
    <Button href="https://github.com/firecubestudios">GitHub</Button>
    <Button href="https://apps.microsoft.com/search/publisher?name=FireCubeStudios&hl=en-us&gl=US">Microsoft Store</Button>
    <Button href="https://twitter.com/FireCubeStudios">Twitter</Button>
    <Button href="https://discord.gg/3WYcKat">Discord</Button>
    <Button href="https://www.youtube.com/@firecubestudios">YouTube</Button>
</div>

<style>
    @import url("https://unpkg.com/fluent-svelte/theme.css");
    :global(body) {
        background-color: var(--fds-solid-background-base);
        color: var(--fds-text-primary);
        color-scheme: light dark;
    }

    .big-f {
        font-size: 6rem;
        color: white;
        position: absolute;
        left: 10%;
        bottom: 40%;
        font-family: "Cascadia Mono", "Fira Code", "Consolas", monospace;
    }

    .small-f {
        font-size: 2rem;
        color: white;
        position: absolute;
        left: 10.4%;
        bottom: 35%;
        font-family: "Cascadia Mono", "Fira Code", "Consolas", monospace;
    }

    .buttons {
        position: absolute;
        left: 10.4%;
        bottom: 28%;
    }
</style>