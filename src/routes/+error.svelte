<script lang="ts">
	import { page } from '$app/stores';
	import img500 from '$assets/3d-casual-life-error-warning-icon.png';
	import img404 from '$assets/3d-casual-life-wind-turbines-in-the-field.png';

	var post: {
		error: string;
		title: string;
		description: string;
		img: string;
		links: { href: string; text: string }[];
	} = {
		error: '500 Internal Error',
		title: "Whoops! There's an error.",
		description: 'Something went wrong on my end. Here are some helpful links:',
		img: img500,
		links: [
			{ href: '/', text: 'Home' },
			{ href: 'https://github.com/karanravindra/', text: 'GitHub' }
		]
	};

	if ($page.error?.message === 'Not Found') {
		post = {
			error: '404 Not Found',
			title: "Whoops! That page doesn't exist.",
			description: 'Something went wrong on my end. Here are some helpful links:',
			img: img404,
			links: [
				{ href: '/', text: 'Home' },
				{ href: 'https://github.com/karanravindra/', text: 'GitHub' }
			]
		};
	}
</script>

<section
	class="flex h-screen flex-col items-center overflow-hidden p-4 max-sm:pt-16 sm:flex-row-reverse sm:justify-between"
>
	<div class="w-2/4 max-w-xs max-sm:pb-16 md:w-1/2 lg:w-1/3 xl:w-1/4">
		<img src={post.img} alt="3d casual life abstract composition with shapes from Icons8" />
	</div>
	<div class="prose xl:prose-lg dark:prose-invert">
		<h4 class="text-primary-600 dark:text-primary-500">{post.error}</h4>
		<h1>{post.title}</h1>
		<p>{post.description}</p>
		<div id="links" class="space-x-4">
			{#each post.links as { href, text }, i}
				<a {href}>{text}</a>
			{/each}
		</div>
	</div>
</section>
