<div class=app>
	<slot />
</div>
<style lang='stylus'>
:global(html)
	height 100%
:global(body)
	height 100%
	margin unset
:global(img)
	display block
	max-width 100%
	height auto
.app
	height 100%
</style>
