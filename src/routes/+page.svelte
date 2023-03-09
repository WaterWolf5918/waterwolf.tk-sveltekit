<script lang="ts">

</script>

<svelte:head>
	<title>WaterWolf.tk - Home</title>
	<meta name="description" content="WaterWolfs Homepage" />
    <meta content="WaterWolf.tk Homepage" property="og:title" />
    <meta content="A basic website for programming projects and other random things" property="og:description" />
    <meta content="https://waterwolf.tk" property="og:url" />
    <!-- <meta content="https://embed.com/embedimage.png" property="og:image" /> -->
    <meta content="#00ffbb" data-react-helmet="true" name="theme-color" />
</svelte:head>

<section>
	<h1>Hi i'm WaterWolf a programming hobbyist</h1>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
		backdrop-filter: blur(8px);
		border: 1px solid rgba(255,255,255,0.24);
		border-radius: 30px;
		-webkit-box-shadow: 0px 0px 73px 1px rgba(0,0,0,0.30);
		-moz-box-shadow: 0px 0px 73px 1px rgba(0,0,0,0.30);
		box-shadow: 0px 0px 73px 1px rgba(0,0,0,0.30);
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
