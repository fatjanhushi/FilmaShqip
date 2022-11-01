<header>
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
<nav>
	<ul>
		<li>
			<a href="#">Menu</a>
		</li>
		<li>
			<a href="#">Watchlist</a>
		</li>
	</ul>

	<input type="search" placeholder="Search" />

	<div id="moviesOrTV">
		<span>Movies</span><span>&nbsp|&nbsp</span><span>TV</span>
	</div>
</nav>

<style lang="scss">
	header {
		display: flex;
		align-items: center;
		justify-content: space-between;
		margin-top: 2rem;
		background-color: white;
		border-top-left-radius: inherit;
		border-top-right-radius: inherit;
	}

	nav {
		background-color: #232323;
		display: flex;
		justify-content: space-between;
		color: white;
		padding-block: 0.3rem;
		ul {
			display: flex;
			align-items: center;
			justify-content: space-evenly;
			li {
				margin-inline: 0.5rem;
				a {
					color: inherit;
				}
			}
		}
		input {
			background-color: transparent;
			width: 50%;
			color: inherit;
			&[type='search'] {
				height: 3rem;
				border-radius: 1rem;
				margin: auto 0.5rem;
				padding-inline: 0.5rem;
			}
		}
		#moviesOrTV {
			margin: auto 0.5rem;
		}
	}
</style>
