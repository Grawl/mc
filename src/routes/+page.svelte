<script lang=ts>
	const host = 'mc.grawl.ru'
	const title = host
	const description = 'Личный сервер Minecraft'
</script>
<svelte:head>
	<title>{title}</title>
	<meta name="description" content={description} />
</svelte:head>
<section class=root>
	<h1>{title}</h1>
	<p>{description}</p>
	<p>
		<a href="https://t.me/mcgrawlru">Telegram</a>
	</p>
	<p>
		<a href="https://mcstatus.io/status/java/{host}" target=_blank>
			<img
				src="https://api.mcstatus.io/v2/widget/java/{host}?transparent=true&dark=true"
				alt=status
				width=860
				height=240
			/>
		</a>
	</p>
</section>
<style lang=stylus>
.root
	display flex
	align-items safe center
	justify-content center
	flex-flow column
	gap 1em
	min-height 100%
	padding 1em
	box-sizing border-box
	background: url('./Enderstone.png') center repeat
	text-align center
	text-transform uppercase
	font-size 1.5em
	font-weight bold
	font-family monospace
	letter-spacing 0.2em
	@media (min-width 400px)
		font-size 2em
p
	margin-block 0.5em
a
	color black
img
	max-height 4em
	width auto
	background url('./Obsidian.webp') center
</style>
