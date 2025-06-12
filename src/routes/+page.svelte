<script>
	const title = 'mc.grawl.ru'
	const description = 'Личный сервер Minecraft'
</script>
<svelte:head>
	<title>{title}</title>
	<meta name="description" content={description} />
</svelte:head>
<section class=root>
	<h1>{title}</h1>
	<p>{description}</p>
	<a href="https://t.me/mcgrawlru">Telegram</a>
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
	text-transform uppercase
	font-size 2em
	font-weight bold
	font-family monospace
	letter-spacing 0.2em
a
	color black
</style>
