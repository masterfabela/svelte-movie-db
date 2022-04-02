<script>
	let count = 0;

	function addOne() {
		count++;
	}
</script>

<h1>Number: {count}</h1>
<p>
	Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>

<a href="/about">Go to about</a>
<button on:click={addOne}>Increment</button>

<style>
	p {
		font-size: 2rem;
	}
</style>
