<script lang="ts">
	import type { FeatherIconNames } from 'feather-icons'
	import feather from 'feather-icons'

	export let icon: FeatherIconNames
	export let {
		size,
		color,
		classes
	}: { size?: number; color?: string; classes?: string } = {
		size: 24,
		color: 'currentColor'
	}
</script>

{@html feather.icons[icon].toSvg({
	width: size,
	height: size,
	stroke: color,
	class: classes
})}
