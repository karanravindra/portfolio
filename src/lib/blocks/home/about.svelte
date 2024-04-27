<script lang="ts">
	import { Button } from 'flowbite-svelte';
</script>

<section id="about">
	<div class="mx-auto max-w-screen-xl bg-gray-50 px-4 py-8 sm:py-16 lg:px-6">
		<h2 class="mb-4 text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white">
			About me
		</h2>
		<div class="flex flex-col md:flex-row md:space-x-4">
			<p class="mb-8 font-light text-gray-500 sm:text-lg dark:text-gray-400">
				Hi, I'm Karan. This is a shared journey to make sense of the complex world around us. I'm
				here to learn out loud, sharing insights as we navigate through the jargon together. It's
				about discovering the simplicity that lies beneath, side by side. Let's learn and grow
				together, one post at a time.
			</p>
			<div>
				<p class="mb-8 font-light text-gray-500 sm:text-lg dark:text-gray-400">
					Learning is about connecting the dots between what we new and old knowledge. My aim is to
					share not just facts, but the journey of understanding them. We'll build our understanding
					from the ground up, retracing they key discoveries advanced us to where we are.
				</p>
			</div>
		</div>
		<div class="flex flex-col space-y-4 sm:flex-row sm:space-x-4 sm:space-y-0">
			<Button color="light" size="lg" href="https://r2.karanravindra.me/Resume.pdf" target="_blank"
				>View Resume<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="ml-2 h-4 w-4"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M13.5 6H5.25A2.25 2.25 0 0 0 3 8.25v10.5A2.25 2.25 0 0 0 5.25 21h10.5A2.25 2.25 0 0 0 18 18.75V10.5m-10.5 6L21 3m0 0h-5.25M21 3v5.25"
					/>
				</svg>
			</Button>
		</div>
	</div>
</section>
