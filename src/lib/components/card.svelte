<script lang="ts">
	export let badge: string = 'Example badge';
	export let badgeColor:
		| 'blue'
		| 'none'
		| 'red'
		| 'yellow'
		| 'green'
		| 'indigo'
		| 'purple'
		| 'pink'
		| 'dark'
		| 'primary' = 'blue';
	export let title: string = 'Example title';
	export let description: string = 'Example description';
	export let href: string = '#';
	import { Badge } from 'flowbite-svelte';
</script>

<article>
	<div class="space-y-3">
		<Badge color={badgeColor}>{badge}</Badge>

		<h2 class="text-2xl font-bold leading-tight tracking-tight text-gray-900 dark:text-white">
			<a {href} class="hover:underline" title="">{title}</a>
		</h2>

		<p class="text-base font-normal text-gray-500 dark:text-gray-400">{description}</p>

		<a
			{href}
			title=""
			class="inline-flex items-center text-base font-semibold leading-tight text-primary-600 hover:underline dark:text-primary-500"
		>
			Read more
			<svg
				aria-hidden="true"
				class="ml-2 h-4 w-4"
				fill="currentColor"
				viewBox="0 0 20 20"
				xmlns="http://www.w3.org/2000/svg"
			>
				<path
					fill-rule="evenodd"
					d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
					clip-rule="evenodd"
				></path>
			</svg>
		</a>
	</div>
</article>
