<script lang="ts">
	import Card from '$lib/components/card.svelte';
</script>

<section id="blog" class="antialiased">
	<div class="mx-auto max-w-screen-xl px-4 py-8 sm:py-16 lg:px-6 lg:py-24">
		<div class="mx-auto max-w-2xl text-center">
			<h2
				class="text-3xl font-extrabold leading-tight tracking-tight text-gray-900 sm:text-4xl dark:text-white"
			>
				My blog
			</h2>
			<p class="mt-4 text-base font-normal text-gray-500 sm:text-xl dark:text-gray-400">
				I write about the things I learn, the things I find interesting and the things I think
				you'll find interesting too.
			</p>
		</div>
		<div class="mt-12 grid grid-cols-1 gap-8 sm:mt-16 lg:grid-cols-2 lg:gap-20">
			<article>
				<a href="#" title="">
					<img
						class="w-full rounded-lg object-cover"
						src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/hero/blog-featured.png"
						alt="featured image"
					/>
				</a>

				<div class="mt-5 space-y-3">
					<span
						class="inline-flex items-center rounded bg-primary-100 px-2.5 py-0.5 text-xs font-medium text-primary-800 dark:bg-primary-900 dark:text-primary-300"
					>
						<svg
							aria-hidden="true"
							class="mr-1 h-3 w-3"
							xmlns="http://www.w3.org/2000/svg"
							viewBox="0 0 20 20"
							fill="currentColor"
						>
							<path
								fill-rule="evenodd"
								d="M12.316 3.051a1 1 0 01.633 1.265l-4 12a1 1 0 11-1.898-.632l4-12a1 1 0 011.265-.633zM5.707 6.293a1 1 0 010 1.414L3.414 10l2.293 2.293a1 1 0 11-1.414 1.414l-3-3a1 1 0 010-1.414l3-3a1 1 0 011.414 0zm8.586 0a1 1 0 011.414 0l3 3a1 1 0 010 1.414l-3 3a1 1 0 11-1.414-1.414L16.586 10l-2.293-2.293a1 1 0 010-1.414z"
								clip-rule="evenodd"
							/>
						</svg>
						Programming
					</span>

					<h2 class="text-2xl font-bold leading-tight tracking-tight text-gray-900 dark:text-white">
						<a href="#" class="hover:underline" title="">
							Releasing code in large corporations is slow - and there is a good reason for it
						</a>
					</h2>

					<div class="flex items-center gap-3">
						<img
							class="h-8 w-8 rounded-full"
							src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/michael-gough.png"
							alt=""
						/>
						<div class="text-md font-medium leading-tight text-gray-900 dark:text-white">
							<div>Michael Gough</div>
							<div class="text-sm font-normal text-gray-500 dark:text-gray-400">
								Posted on Jan 31
							</div>
						</div>
					</div>

					<p class="text-base font-normal text-gray-500 dark:text-gray-400">
						One of the things I always loved about the web is its immediacy. You write a piece of
						code, publish it somewhere and people can access it.
					</p>

					<a
						href="#"
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

			<div class="space-y-8">
				<Card
					badge="Web Development"
					title="How to build a blog with SvelteKit"
					description="In this tutorial, we'll build a blog with SvelteKit, Tailwind CSS and Markdown."
				/>
				<Card
					badge="Machine Learning"
					badgeColor="green"
					title="Machine learning for beginners"
					description="In this tutorial, we'll build a simple machine learning model using Python. No prior experience required."
				/>
				<Card
					badge="Machine Learning"
					badgeColor="green"
					title="Build a classifer with PyTorch"
					description="In this tutorial, we'll build a simple image classifier using PyTorch. We will train a model to classify images of handwritten digits."
				/>
			</div>
		</div>
	</div>
</section>
