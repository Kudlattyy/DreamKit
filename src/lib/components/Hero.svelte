<main>
	<div class="main journals">
		<div class="journals__tittle">Journals</div>
		<div class="journals__dreams"></div>
		<div class="journals__add-Dream"></div>
	</div>
</main>

<style lang="scss">
	main {
		height: 100vh;
		width: 100vw;
		display: flex;
		.journals {
			height: 100vh;
			width: 100vw;
			padding: 5vh 4vw;
			&__tittle {
				height: auto;
				color: var(--tittle-font-color);
				font-size: var(--tittle-font-size);
				font-family: var(--tittle-font-style);
			}
			&__dreams {
				height: 85vh;
			}
			&__add-Dream {
				height: 5vh;
			}
		}
	}
</style>
