<script>
	export let name;
	let count = 0;

	function handleClick(){
		count += 1;
	}
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello {name}! Nice to meet you!</h1>
<p>
	You got a problem?
</p>

<button on:click={handleClick}>
Clicked {count} {count === 1 ? 'time' : 'times'}
</button>