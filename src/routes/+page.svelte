<body>
	<section class="hero">
		<div class="hero-area">
			<div class="hero-text">
				<h1>Sonia William</h1>
				<p>Front-End Developer</p>
				<div class="button">About me</div>
			</div>
		</div>
	</section>
</body>

<style lang="scss">
	body {
		font-family: 'Mali', sans-serif;
	}

	h1 {
		font-size: 90px;
		margin: 0;
	}

	p {
		margin: 1px;
		font-size: 35px;
	}

	.hero-area {
		display: flex;
		flex-direction: column;
		height: 100vh;
		justify-content: center;
	}

	.hero-text {
		margin-left: 80px;
		margin-bottom: 200px;
	}

	.button {
		width: 200px;
		height: 60px;
		border-radius: 40px;
		background-color: var(--primary);
		text-align: center;
		color: var(--paper);
		font-size: 27px;
		padding-top: 20px;
		margin-top: 20px;
		&:hover {
			background-color: var(--accent2);
			color: var(--secondary);
		}
		&:active {
			background-color: #eddd98;
			color: var(--secondary);
		}
	}
</style>
