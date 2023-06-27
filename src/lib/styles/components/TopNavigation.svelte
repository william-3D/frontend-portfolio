<head>
	<script src="https://kit.fontawesome.com/6a7d4cd279.js" crossorigin="anonymous"></script>
</head>

<nav class="top-nav">
	<a class="logo" href="#hero">Sonia W</a>

	<ul id="nav-list">
		<li>
			<a href="#hero">Home</a>
		</li>
		<li>
			<a href="#about-me">About</a>
		</li>
		<li>
			<a href="#projects">Projects</a>
		</li>
		<li>
			<a href="#contact">Contact</a>
		</li>
	</ul>
	<button class="hamburger" id="hamburger">
		<i class="fas fa-bars" />
	</button>
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
			&.show {
				display: block;
			}
			&:focus {
				outline: 0;
			}
		}

		.hamburger {
			display: none;
		}

		@media only screen and (max-width: 1000px) {
			/*.hamburger {
				display: block;
				border: 0;
				background-color: transparent;
				color: var(--primary);
				font-size: 30px;
				margin: 20px;
				align-self: flex-end;
			}

			ul {
				display: none;
				background-color: var(--paper);
				margin: 0px;
			}*/

			nav {
				display: flex;
				flex-direction: column-reverse;
				background-color: var(--paper);
			}

			.logo {
				display: none;
			}
		}
	}
</style>
