<nav class="top-nav">
	<a class="logo" href="#hero">Sonia W</a>

	<ul>
		<li>
			<a href="#hero">Home</a>
		</li>
		<li>
			<a href="#about-me">About</a>
		</li>
		<li>
			<a href="#projects">Projects</a>
		</li>
	</ul>
</nav>

<style lang="scss">
	nav {
		display: flex;
		justify-content: space-between;
		align-items: center;
		line-height: 48px;
		padding-left: 24px;
		position: fixed;
		top: 0;
		left: 0;
		right: 0;
		background-color: var(--paper);

		.logo {
			color: var(--primary);
			font-weight: bold;
			font-size: 25px;
		}

		a {
			text-decoration: none;
			color: var(--secondary);
			&:hover {
				color: var(--primary);
				text-decoration: underline;
			}
		}
		ul {
			list-style: none;
			margin: 0;
			padding: 0;
			li {
				display: inline-block;
				a {
					display: inline-block;
					padding: 8px 16px;
				}
			}
		}
	}
</style>
