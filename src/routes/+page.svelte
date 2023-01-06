<script lang="ts">
	let count: number = 0

	const increaseCount = () => {
		count += 1
	}
</script>

<h1>count : {count}</h1>
<button on:auxclick={increaseCount}>Click</button>