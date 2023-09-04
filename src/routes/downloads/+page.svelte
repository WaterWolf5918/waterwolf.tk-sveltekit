<svelte:head>
	<title>About</title>
	<meta name="description" content="Download list for projects" />
</svelte:head>

<div class="text-column">
	<h1>Download list for projects</h1>
	<section>
		<ul>
			<li>
				<div id="download-object">
					<p><a href="/">WatchRPC v2</a></p>
				</div>
			</li>
			<li>
				<div id="download-object">
					<p><a href="./downloads/KillThatAD">Kill That AD</a></p>
				</div>
			</li>
		</ul>
	</section>
</div>

<style>
	ul {
		position: relative;
		padding: 0;
		margin: 0;
		display: flex;
		justify-content: center;
		align-items: center;
		list-style: none;
		background: rgba(1, 1, 1, 0.474);
		background-size: contain;
	}

	li {
		position: relative;
		height: 100%;
		padding-left: 5px;
		padding-right: 5px;
		width: max-content;
		border: 1px solid gray;
	}

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

	/* #download-object{
		display: flex;
		padding-left: 5px;
		padding-right: 5px;
		border: 1px solid rgb(255, 255, 255);
	} */
</style>