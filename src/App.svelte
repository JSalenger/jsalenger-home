<svelte:head>
	<meta property="og:title" content="Jón Salenger" />
	<meta property="og:image" content="/blob.png" />

	<meta property="og:description" 
		content="The very cool website for Jón Salenger, some would even describe it as PogChamp" />
</svelte:head>

<main>
	<h1>Jón Salenger</h1>
	<p>I make cool things like this green blob</p>

	<svg style="overflow:hidden;" class="svg" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
		<path fill="#24A148" d="M50,-43.3C61.8,-38.1,66.4,-19.1,61.5,-4.9C56.5,9.2,42.1,18.4,30.2,33.6C18.4,48.8,9.2,70,-2.8,72.8C-14.7,75.6,-29.5,59.9,-42.2,44.7C-54.9,29.5,-65.7,14.7,-61.5,4.2C-57.3,-6.4,-38.3,-12.8,-25.5,-18C-12.8,-23.2,-6.4,-27.1,6.3,-33.5C19.1,-39.8,38.1,-48.5,50,-43.3Z" transform="translate(100 100)" />
	</svg>
</main>

<style>
	main {
		margin: auto;
		text-align: center;
		max-width: 240px;
	}

	p {
		font-size: 90%;
	}

	h1 {
		color: #24A148;
		text-transform: uppercase;
		font-size: 250%;
		font-weight: 100;
	}
	
	.svg {
		max-width: 100%;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}

		p {
			font-size: 1.5rem;
		}

		h1 {
			font-size: 5rem;
		}

		.svg {
			max-width: 50rem;
		}
	}
</style>