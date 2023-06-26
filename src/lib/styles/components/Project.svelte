<script lang="ts">
	export let project: any;
</script>

<div class="projects">
	<h2>Projects</h2>
	<div class="project-container">
		<div class="project-card">
			<img src="src/lib/assets/rps.png" alt="Rock Paper Scissors" />
			<h3>Rock Paper Scissors</h3>
			<p>The grade school classic.</p>
			<p id="live" class="one">
				<a href="https://william-3d.github.io/rock-paper-scissors/">Live preview</a>
			</p>
			<p><a href="https://github.com/william-3D/rock-paper-scissors">Code</a></p>
		</div>
		<div class="project-card">
			<img src="src/lib/assets/etch.png" alt="Etch A Sketch" />
			<h3>Etch A Sketch</h3>
			<p>For the inner child in us all!</p>
			<p id="live" class="two">
				<a href="https://william-3d.github.io/etch-a-sketch/">Live preview</a>
			</p>
			<p><a href="https://github.com/william-3D/etch-a-sketch">Code</a></p>
		</div>
		<div class="project-card">
			<img src="src/lib/assets/calculator.png" alt="Calculator" />
			<h3>Calculator</h3>
			<p>Built to deepen my understanding of vanilla JS.</p>
			<p id="live" class="three">
				<a href="https://william-3d.github.io/calculator">Live preview</a>
			</p>
			<p><a href="https://github.com/william-3D/calculator">Code</a></p>
		</div>
		<div class="project-card">
			<img src="src/lib/assets/amazon.png" alt="Amazon Clone" />
			<h3>Amazon Clone</h3>
			<p>Aimed at learning React, Tailwind CSS & Redux.</p>
			<p class="four">In progress!</p>
		</div>
	</div>
</div>

<style lang="scss">
	.project-card {
		width: 300px;
		height: 500px;
		box-shadow: 5px 5px 20px var(--accent1);
		border-radius: 40px;
		h3 {
			font-size: 25px;
			color: #083f99;
		}
		p {
			font-size: 20px;
		}
		a {
			color: var(--secondary);
			text-decoration: none;
			&:hover {
				color: var(--primary);
			}
			&:active {
				color: var(--accent2);
			}
		}
		.one {
			margin-top: 30px;
		}
		.two {
			margin-top: 30px;
		}
		.three {
			margin-top: 6px;
		}
		.four {
			margin-top: 35px;
		}
	}

	.project-container {
		display: flex;
		justify-content: space-around;
	}

	.projects {
		display: flex;
		flex-direction: column;
		text-align: center;
		padding: 80px;
		img {
			margin-top: 25px;
			width: 250px;
			border-radius: 150px;
		}
	}
</style>
