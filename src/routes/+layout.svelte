<script>
	import favicon from "$lib/assets/favicon.svg";

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}

<footer>
	<p>©️ polimi 2026</p>
</footer>

<!-- nel file page abbiamo detto che tutti i paragrafi devono essere deep pink
 ma svelte prende il nostro css e lo incapsula solo nell'altro file 	
 p {
	color: deeppink;
	}
-->

<style>
	:global(p) {
		color: deeppink;
	}
</style>

<!-- usando global tutti i paragrafi (p) sono colorati in deeppink
-->