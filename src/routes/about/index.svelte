<script context="module">
	import FontAwesomeIcon from 'fontawesome-svelte/src/FontAwesomeIcon.svelte';
import SvelteTooltip from 'svelte-tooltip';
	import FontAwesome from './_fontAwesome.svelte';
</script>

<svelte:head>
	<title>About</title>
</svelte:head>

<div class="content">
	<div class="timeline">
		<div class="year">1998</div>
		<div class="line-block">
			<div class="line"></div>
			<SvelteTooltip tip="長崎県松浦市に生まれる．" right color="#FBC7F7">
				<div class="circle">
					<span class="m-d">
						<FontAwesome iconName="birthday-cake" />
					</span>
				</div>
			</SvelteTooltip>
			<div class="line"></div>
		</div>

		<div class="year">2002</div>
		<div class="line-block">
			<div class="line"></div>
			<SvelteTooltip tip="PC（当時のMacintosh）を触り始める．" right color="#FBC7F7">
				<div class="circle">
					<span class="m-d">
						<FontAwesome iconName="laptop" />
					</span>
				</div>
			</SvelteTooltip>
			<div class="line"></div>
		</div>

		<div class="year">2005</div>
		<div class="line-block">
			<div class="line"></div>
			<SvelteTooltip tip="長崎大学教育学部附属小学校入学" right color="#FBC7F7">
				<div class="circle">
					<span class="m-d">
						<FontAwesome iconName="graduation-cap" />
					</span>
				</div>
			</SvelteTooltip>
			<div class="line"></div>
		</div>

		<div class="year">2011</div>
		<div class="line-block">
			<div class="line"></div>
			<SvelteTooltip tip="長崎大学教育学部附属中学校入学" right color="#FBC7F7">
				<div class="circle">
					<span class="m-d">
						<FontAwesome iconName="graduation-cap" />
					</span>
				</div>
			</SvelteTooltip>
			<div class="line"></div>
			<SvelteTooltip tip="十進BASICに出会う。プログラミングに興味を持ったきっかけである。" right color="#FBC7F7">
				<div class="circle">
					<span class="m-d">
						<FontAwesome iconName="laptop" />
					</span>
				</div>
			</SvelteTooltip>
			<div class="line"></div>
			<SvelteTooltip tip="VisualBasicで人生初のデスクトップアプリ「平方根計算機」を開発する" right color="#FBC7F7">
				<div class="circle">
					<span class="m-d">
						<FontAwesome iconName="square-root-alt" />
					</span>
				</div>
			</SvelteTooltip>
			<div class="line"></div>
		</div>

		<div class="year">2014</div>
		<div class="line-block">
			<div class="line"></div>
			<SvelteTooltip tip="長崎県立長崎西高等学校普通科普通コース入学" right color="#FBC7F7">
				<div class="circle">
					<span class="m-d">
						<FontAwesome iconName="graduation-cap" />
					</span>
				</div>
			</SvelteTooltip>
			<div class="line"></div>
		</div>

		<div class="year">2017</div>
		<div class="line-block">
			<div class="line"></div>
			<SvelteTooltip tip="静岡大学入学" right color="#FBC7F7">
				<div class="circle">
					<span class="m-d">
						<FontAwesome iconName="graduation-cap" />
					</span>
				</div>
			</SvelteTooltip>
			<div class="line"></div>
		</div>
		
	</div>
</div>

<style>
	.content {
		width: 100%;
		max-width: var(--column-width);
		margin: var(--column-margin-top) auto 0 auto;
	}

	.timeline {
		text-align: center;
	}

	.year {
		margin: 0 auto;
	}

	.circle {
		height: 40px;
		width: 40px;
		border: 4px solid #D62AD0;
		background-color: #FBC7F7;
		border-radius: 50%;
		margin: 0 auto;
		line-height: 32px;
		display: grid;
		place-items: center;
	}

	.m-d {
		
	}
	
	.line {
		height: 32px;
		width: 2px;
		background-color: #FBC7F7;
		margin: 0 auto;
	}
	
</style>
