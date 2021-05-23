<script>
	import Surname from './Surname.svelte'
    import Box from './Box.svelte'
	export let name;
    export let surname;
</script>

<main>
	<h1>Hello {name} {surname}!</h1>
	<h3>Hello Kat</h3>
	<Surname/>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: powderblue;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>