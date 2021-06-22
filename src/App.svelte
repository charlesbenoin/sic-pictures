<script>
	import router from "page"
	import Projets from './Projets.svelte'
	import Accueil from './Accueil.svelte'
	import Partenaires from './Partenaires.svelte'
	import Contact from './Contact.svelte'

	let page;
	router('/', () => page = Accueil)
	router('/projets', () => page = Projets)
    router('/partenaires', () => page = Partenaires)
    router('/contact', () => page = Contact)

	router.start()
</script>

<svelte:component this={page} />

<style global>

	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}

	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>