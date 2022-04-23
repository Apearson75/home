<script lang="ts">
	let count = 0;
	const increment = () => {
		count++;
		if (count >= 10) {
			count = 0;
		}
	}
</script>

<section>
	<button on:click="{increment}" class="font-semibold text-white my-2 bg-gray-600 rounded-md w-40">
		Click to count: {count}
	</button>
</section>