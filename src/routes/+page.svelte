<script>
    //qui posso scrivere lo javascript, quindi hava, html, css
    // ora entriamo nel vivo dello stato, svelte tiene conto se si aggiornerà lo 0
    //è una variabile
    import ClicksCounter from "$lib/components/ClicksCounter.svelte";
</script>

<h1>Welcome to SvelteKit</h1>
<p>
    Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the
    documentation
</p>

<ClicksCounter />

<style>
    h1 {
        color: deepskyblue;
    }
</style>
