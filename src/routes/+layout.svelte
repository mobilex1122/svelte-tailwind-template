<script>
	import '../app.css';
</script>

<slot />

<style lang="postcss">
	:global(html) {
		@apply bg-white dark:bg-gray-950 dark:text-white;
	}
</style>
