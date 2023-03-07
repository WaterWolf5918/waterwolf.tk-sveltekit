<svelte:head>
	<title>About</title>
	<meta name="description" content="Project list" />
</svelte:head>

<div class="text-column">
	<h1>Project list</h1>
	<section>
		<ul>
			<li>
				<div id="download-object">
					<p><a href="">WatchRPC v2</a></p>
				</div>
			</li>
			<li>
				<div id="download-object">
					<p><a href="">WatchRPC Lite</a></p>
				</div>
			</li>
			<li>
				<div id="download-object">
					<p><a href="">waterwolf.tk</a></p>
				</div>
			</li>
		</ul>
	</section>
</div>

<style>
	ul {
		padding: 0;

		list-style: none;
		background: rgba(1, 1, 1, 0.474);
		background-size: contain;
		border: 1px solid rgb(255,255,255);
	}

	li {
		/* padding: 8px 16px; */
		position: relative;
		height: 100%;
		padding-left: 16px;
		padding-right: 16px;
		
		border-bottom: 1px solid rgb(255,255,255);
	}

	li:last-child {
		border-bottom: none
	}

	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
		backdrop-filter: blur(5px);
		border: 1px solid rgb(175, 175, 175);
		border-radius: 30px;
		-webkit-box-shadow: 0px 0px 73px 1px rgba(0,0,0,0.30);
		-moz-box-shadow: 0px 0px 73px 1px rgba(0,0,0,0.30);
		box-shadow: 0px 0px 73px 1px rgba(0,0,0,0.30);
	}

	#download-object{
		display: block;

	}
</style>