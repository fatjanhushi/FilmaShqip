<script lang="ts">
	import '../app.scss'
	import Header from './header.svelte'
	import Footer from './footer.svelte'
</script>

<div class="container">
	<Header />
	<div class="content">
		<slot />
	</div>
	<Footer />
</div>

<style lang="scss">
	.container {
		border-radius: 1rem;
		margin-inline: auto;
		width: 80%;
		max-width: 80rem;
		box-shadow: 0px 0px 0.5rem #ccc;
	}

	.content {
		background-color: white;
		padding-inline: 0.3rem;
	}
</style>
