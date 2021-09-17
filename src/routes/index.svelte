<script>
	
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<div class="content">
	<div class="greeting-icon-area">
		<svg class="path">
			<use xlink:href="../static/fuwasegu.svg#fuwasegu"></use>
		</svg>
	</div>
	<div class="icon-area">
		<img src="../static/icon.jpg" alt="icon" class="icon">
	</div>
</div>

<style>
	.content {
		width: 100%;
		max-width: var(--column-width);
		margin: var(--column-margin-top) auto 0 auto;
	}

	use{
		width: 100%;
	}

	.path {
		fill: none; /*塗り*/
		stroke: #D62AD0; /*線の色*/
		stroke-dasharray: 2000;/*線の間隔*/
		stroke-dashoffset: 0;/*線の開始位置*/
		stroke-width: 1;/*線の太さ*/
		animation: write 3s ease-in forwards;
		-webkit-animation: write 3s ease-in forwards;
		width: 100%;
	}

	@keyframes write {
		0% {
			stroke-dashoffset: 2000;
			fill:transparent;
		}
		50% {
			fill:transparent;
		}
		100% {
			stroke-dashoffset: 0;
			fill:#FBC7F7;
		}
	}

	@-webkit-keyframes write {
		0% {
			stroke-dashoffset: 2000;
			fill:transparent;
		}
		50% {
			fill:transparent;
		}
		100% {
			stroke-dashoffset: 0;
			fill:#FBC7F7;
		}
	}

	img.icon {
		max-width: 300px;
		width: 100%;
		display: block;
		margin-left: auto;
		margin-right: auto;
		margin-top: 30px; 
		animation: fuwafuwa 2s infinite;
	}

	@keyframes fuwafuwa {
		0% {
			transform: translateY(0px);
		}
		50% {
			transform: translateY(-30px);
		}
		100% {
			transform: translateY(0px);
		}
	}

</style>
