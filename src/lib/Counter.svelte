<script lang="ts">
	let count = 0;
	const increment = () => {
		count++;
	}
</script>

<section>
	<button on:click="{increment}" class="font-semibold text-white my-2 bg-gray-600 rounded-md w-40">
		Click to count: {count}
	</button>
</section>