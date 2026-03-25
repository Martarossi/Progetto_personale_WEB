<script>
    let {initialCount: count = $bindable()} = $props()
    //si può permettere di dire che fa il collegamento al parents (page.svelte)
    let doubled = $derived(count * 2)
</script>

<h3>Clicks Counter</h3>

<button onclick={() => count++}>
clicks: {count}
</button>

<span> doubled is {doubled}</span>