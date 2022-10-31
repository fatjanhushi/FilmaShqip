<header class="container">
	<figure>
		<img
			src="https://www.getautismactive.com/wp-content/uploads/2021/01/Test-Logo-Circle-black-transparent.png"
			alt="Logo"
			width="90px"
			height="90px"
		/>
	</figure>

	<figure>
		<img
			src="https://www.getautismactive.com/wp-content/uploads/2021/01/Test-Logo-Circle-black-transparent.png"
			alt="Logo"
			width="90px"
			height="90px"
		/>
	</figure>
</header>
<nav class="container">
	<ul>
		<li>
			<a href="#">Menu</a>
		</li>
		<li>
			<a href="#">Watchlist</a>
		</li>
	</ul>

	<input type="search" placeholder="Search" />

	<span>Movies</span><span>&nbsp|&nbsp</span><span>TV</span>
</nav>

<style lang="scss">
	header {
		display: flex;
		align-items: center;
		justify-content: space-between;
		margin-top: 2rem;
		background-color: white;
		border-top-left-radius: 1rem;
		border-top-right-radius: 1rem;
	}

	nav {
		background-color: #232323;
		display: flex;
		color: white;
		ul {
			display: flex;
			align-items: center;
			justify-content: space-around;
			li {
				padding: 1rem 0.5rem;
				a {
					color: inherit;
				}
			}
		}
		input {
			background-color: transparent;
			width: 100%;
			color: inherit;
			&[type='search'] {
				height: 3rem;
				border-radius: 1rem;
				margin: auto 1rem;
				padding-inline: 0.5rem;
			}
		}
		span {
			margin: auto 0;
		}
	}
</style>
