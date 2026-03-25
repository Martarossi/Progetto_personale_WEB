<script>
    //qui posso scrivere lo javascript, quindi hava, html, css
    // ora entriamo nel vivo dello stato, svelte tiene conto se si aggiornerà lo 0
    //è una variabile
    let count = $state(0)
    let doubled = $derived(count * 2)
</script>

<h3>Clicks Counter</h3>

<button onclick={() => count++}>
clicks: {count}
</button>

<span> doubled is {doubled}</span>