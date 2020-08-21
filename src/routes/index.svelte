<style>
	h1, figure, p {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.4em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
	}

	img {
		height: 40vmin;
		margin: 1.3em 0;
	}

	p {
		margin: 1em auto;
	}

	nav {
		margin-top: 32px;
		display: flex;
		justify-content: center;
	}

	nav a {
		color: #159497;
		font-weight: 500;
		text-decoration: none;
		margin: 0 24px;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 2.2em;
		}
	}
</style>

<svelte:head>
	<title>Sapper Electron App Template</title>
</svelte:head>

<h1>Welcome to Electron-Sapper App!</h1>

<figure>
	<img alt='Sapper Logo' src='/logo-512.png'>
	<figcaption>Visit the <a href="https://sapper.svelte.dev/docs">Sapper tutorial</a> to learn how to build Sapper apps.</figcaption>
</figure>

<p><strong>Try editing this file (src/routes/index.svelte) to test live reloading.</strong></p>

<nav>
	<a href="https://sapper.svelte.dev/faq/">FAQ</a>
	<a href="https://svelte.dev/">Svelte</a>
	<a href="https://discord.com/invite/yy75DKs">Discord</a>
	<a href="https://github.com/sveltejs/sapper">GitHub</a>
</nav>