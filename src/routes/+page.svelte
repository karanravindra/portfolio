<script lang="ts">
	import img from '$assets/3d-casual-life-abstract-composition-with-shapes.png';
	import { Card } from 'flowbite-svelte';
</script>

<section id="hero" class="py-4">
	<div class="mx-auto grid max-w-screen-xl px-4 py-8 lg:grid-cols-12 lg:gap-8 lg:py-16 xl:gap-0">
		<div class="mr-auto place-self-center lg:col-span-7">
			<h1
				class="mb-4 max-w-2xl text-4xl font-extrabold leading-none tracking-tight md:text-5xl xl:text-6xl dark:text-white"
			>
				Turning Complexity into Clarity
			</h1>
			<p
				class="mb-6 max-w-2xl font-light text-gray-500 md:text-lg lg:mb-8 lg:text-xl dark:text-gray-400"
			>
				My mission: To bring clarity to a world filled with big words and know-it-alls. With the
				right context, everything thing is intuitive.
			</p>
			<a
				href="#"
				class="mr-3 inline-flex items-center justify-center rounded-lg bg-primary-700 px-5 py-3 text-center text-base font-medium text-white hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 dark:focus:ring-primary-900"
			>
				Get started
				<svg
					class="-mr-1 ml-2 h-5 w-5"
					fill="currentColor"
					viewBox="0 0 20 20"
					xmlns="http://www.w3.org/2000/svg"
					><path
						fill-rule="evenodd"
						d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
						clip-rule="evenodd"
					></path></svg
				>
			</a>
			<a
				href="#"
				class="inline-flex items-center justify-center rounded-lg border border-gray-300 px-5 py-3 text-center text-base font-medium text-gray-900 hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:border-gray-700 dark:text-white dark:hover:bg-gray-700 dark:focus:ring-gray-800"
			>
				Speak to Sales
			</a>
		</div>
		<div class="hidden lg:col-span-5 lg:mt-0 lg:flex">
			<img
				src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/hero/phone-mockup.png"
				alt="mockup"
			/>
		</div>
	</div>
</section>
<section id="about">
	<div class="mx-auto max-w-screen-xl px-4 py-8 sm:py-16 lg:px-6">
		<h2 class="mb-4 text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white">
			About me
		</h2>
		<div class="flex flex-row space-x-4">
			<p class="mb-8 font-light text-gray-500 sm:text-xl dark:text-gray-400">
				Hi, I'm Karan. This is a shared journey to make sense of the complex world around us. I'm
				here to learn out loud, sharing insights as we navigate through the jargon together. It's
				about discovering the simplicity that lies beneath, side by side. Let's learn and grow
				together, one post at a time.
			</p>
			<div>
				<p class="mb-8 font-light text-gray-500 sm:text-xl dark:text-gray-400">
					Learning is about connecting the dots between what we new and old knowledge. My aim is to
					share not just facts, but the journey of understanding them. We'll build our understanding
					from the ground up, retracing they key discoveries advanced us to where we are.
				</p>
			</div>
		</div>
		<div class="flex flex-col space-y-4 sm:flex-row sm:space-x-4 sm:space-y-0">
			<a
				href="#"
				class="inline-flex items-center justify-center rounded-lg border border-gray-300 px-4 py-2.5 text-center text-base font-medium text-gray-900 hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:border-gray-600 dark:text-white dark:hover:bg-gray-700 dark:focus:ring-gray-600"
			>
				View Resume
			</a>
		</div>
	</div>
</section>
<section id="blog">
	<div class="mx-auto max-w-screen-xl px-4 py-8 sm:py-16 lg:px-6">
		<div class="mx-auto max-w-screen-sm text-center">
			<h2
				class="mb-4 text-3xl font-extrabold tracking-tight text-gray-900 lg:text-4xl dark:text-white"
			>
				Our Blog
			</h2>
			<p class="mb-8 font-light text-gray-500 sm:text-xl lg:mb-16 dark:text-gray-400">
				We use an agile approach to test assumptions and connect with the needs of your audience
				early and often.
			</p>
		</div>
		<div
			class="mb-16 grid gap-8 lg:grid-cols-3 lg:divide-x lg:divide-gray-200 dark:lg:divide-gray-700"
		>
			<article>
				<a href="#">
					<img
						class="mb-5 rounded-lg"
						src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/blog/google-hq.png"
						alt="blog image"
					/>
				</a>
				<h2 class="my-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
					<a href="#">SEO Basics: Beginner's Guide to SEO Success</a>
				</h2>
				<p class="mb-4 font-light text-gray-500 dark:text-gray-400">
					Over the past year, Volosoft has undergone many changes! After months of preparation and
					some hard work, we moved to our new office.
				</p>
				<a
					href="#"
					class="inline-flex items-center font-medium text-primary-600 hover:underline dark:text-primary-500"
				>
					Read more
					<svg
						class="ml-2 h-4 w-4"
						fill="currentColor"
						viewBox="0 0 20 20"
						xmlns="http://www.w3.org/2000/svg"
						><path
							fill-rule="evenodd"
							d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
							clip-rule="evenodd"
						></path></svg
					>
				</a>
			</article>
			<div class="space-y-8 lg:pl-8">
				<article>
					<h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
						<a href="#">How to quickly deploy a static website</a>
					</h2>
					<p class="mb-4 font-light text-gray-500 dark:text-gray-400">
						Over the past year, Volosoft has undergone many changes! After months of preparation and
						some hard work, we moved to our new office.
					</p>
					<a
						href="#"
						class="inline-flex items-center font-medium text-primary-600 hover:underline dark:text-primary-500"
					>
						Read more
						<svg
							class="ml-2 h-4 w-4"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
								clip-rule="evenodd"
							></path></svg
						>
					</a>
				</article>
				<article>
					<h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
						<a href="#">What is SEO? Search Engine Optimization Explained</a>
					</h2>
					<p class="mb-4 font-light text-gray-500 dark:text-gray-400">
						Over the past year, Volosoft has undergone many changes! After months of preparation and
						some hard work, we moved to our new office.
					</p>
					<a
						href="#"
						class="inline-flex items-center font-medium text-primary-600 hover:underline dark:text-primary-500"
					>
						Read more
						<svg
							class="ml-2 h-4 w-4"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
								clip-rule="evenodd"
							></path></svg
						>
					</a>
				</article>
				<article>
					<h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
						<a href="#">Spotify's Car Thing available to all premium users</a>
					</h2>
					<p class="mb-4 font-light text-gray-500 dark:text-gray-400">
						Over the past year, Volosoft has undergone many changes! After months of preparation and
						some hard work, we moved to our new office.
					</p>
					<a
						href="#"
						class="inline-flex items-center font-medium text-primary-600 hover:underline dark:text-primary-500"
					>
						Read more
						<svg
							class="ml-2 h-4 w-4"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
								clip-rule="evenodd"
							></path></svg
						>
					</a>
				</article>
			</div>
			<div class="space-y-8 lg:pl-8">
				<article>
					<h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
						<a href="#">How to Rank Higher on Google (6 Easy Steps)</a>
					</h2>
					<p class="mb-4 font-light text-gray-500 dark:text-gray-400">
						Over the past year, Volosoft has undergone many changes! After months of preparation and
						some hard work, we moved to our new office.
					</p>
					<a
						href="#"
						class="inline-flex items-center font-medium text-primary-600 hover:underline dark:text-primary-500"
					>
						Read more
						<svg
							class="ml-2 h-4 w-4"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
								clip-rule="evenodd"
							></path></svg
						>
					</a>
				</article>
				<article>
					<h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
						<a href="#">12 SEO Best Practices That Everyone Should Follow</a>
					</h2>
					<p class="mb-4 font-light text-gray-500 dark:text-gray-400">
						Over the past year, Volosoft has undergone many changes! After months of preparation and
						some hard work, we moved to our new office.
					</p>
					<a
						href="#"
						class="inline-flex items-center font-medium text-primary-600 hover:underline dark:text-primary-500"
					>
						Read more
						<svg
							class="ml-2 h-4 w-4"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
								clip-rule="evenodd"
							></path></svg
						>
					</a>
				</article>
				<article>
					<h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
						<a href="#">How to schedule your Tweets to send later</a>
					</h2>
					<p class="mb-4 font-light text-gray-500 dark:text-gray-400">
						Over the past year, Volosoft has undergone many changes! After months of preparation and
						some hard work, we moved to our new office.
					</p>
					<a
						href="#"
						class="inline-flex items-center font-medium text-primary-600 hover:underline dark:text-primary-500"
					>
						Read more
						<svg
							class="ml-2 h-4 w-4"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
								clip-rule="evenodd"
							></path></svg
						>
					</a>
				</article>
			</div>
		</div>
	</div>
</section>
<section id="projects" class="antialiased">
	<div class="mx-auto max-w-screen-xl px-4 py-8 sm:py-16 lg:px-6 lg:py-24">
		<div class="mx-auto max-w-2xl text-center">
			<h2
				class="text-3xl font-extrabold leading-tight tracking-tight text-gray-900 sm:text-4xl dark:text-white"
			>
				Our work
			</h2>
			<p class="mt-4 text-base font-normal text-gray-500 sm:text-xl dark:text-gray-400">
				Flowbite helps you connect with friends, family and communities of people who share your
				interests.
			</p>
		</div>

		<div class="mt-12 space-y-16 sm:mt-16">
			<div
				class="flex flex-col gap-y-8 sm:gap-y-12 lg:flex-row lg:items-center lg:gap-x-16 xl:gap-x-24"
			>
				<div>
					<img
						class="w-full rounded-lg object-cover shadow-lg dark:hidden"
						src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/case-study/flowbite-dashboard.jpg"
						alt=""
					/>
					<img
						class="hidden w-full rounded-lg object-cover shadow-lg dark:block"
						src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/case-study/flowbite-dashboard-dark.jpg"
						alt=""
					/>
				</div>

				<div class="w-full shrink-0 space-y-6 lg:max-w-lg xl:max-w-2xl">
					<div class="space-y-3">
						<h3 class="text-3xl font-bold leading-tight text-gray-900 sm:text-4xl dark:text-white">
							Flowbite's dashboard
						</h3>
						<a
							href="https://flowbite.com"
							title=""
							class="inline-flex items-center text-lg font-medium text-primary-600 hover:underline dark:text-primary-500"
						>
							https://flowbite.com
							<svg
								aria-hidden="true"
								class="ml-2.5 h-5 w-5"
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 20 20"
								fill="currentColor"
							>
								<path
									d="M11 3a1 1 0 100 2h2.586l-6.293 6.293a1 1 0 101.414 1.414L15 6.414V9a1 1 0 102 0V4a1 1 0 00-1-1h-5z"
								/>
								<path
									d="M5 5a2 2 0 00-2 2v8a2 2 0 002 2h8a2 2 0 002-2v-3a1 1 0 10-2 0v3H5V7h3a1 1 0 000-2H5z"
								/>
							</svg>
						</a>
						<p class="text-base font-normal text-gray-500 sm:text-lg dark:text-gray-400">
							Flowbite helps you connect with friends, family and communities of people who share
							your interests. Connecting with your friends and family as well as discovering new
							ones is easy with features like Groups.
						</p>
					</div>

					<div class="flex items-center gap-2.5">
						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-html5"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/html5.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-html5"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							HTML5
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>

						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-css3"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/css-3.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-css3"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							CSS3
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>

						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-javascript"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/javascript.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-javascript"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							JavaScript
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>

						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-tailwind-css"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/tailwind-css.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-tailwind-css"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							Tailwind CSS
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>

						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-typescript"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/typescript.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-typescript"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							TypeScript
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>
					</div>

					<a
						href="#"
						title=""
						class="inline-flex items-center justify-center rounded-lg bg-primary-700 px-5 py-2.5 text-center text-sm font-medium text-white hover:bg-primary-800 focus:outline-none focus:ring-4 focus:ring-primary-300 dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
						role="button"
					>
						View case study
						<svg
							aria-hidden="true"
							class="-mr-1 ml-2 h-5 w-5"
							xmlns="http://www.w3.org/2000/svg"
							viewBox="0 0 20 20"
							fill="currentColor"
						>
							<path
								fill-rule="evenodd"
								d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
								clip-rule="evenodd"
							/>
						</svg>
					</a>
				</div>
			</div>

			<div
				class="flex flex-col gap-y-8 sm:gap-y-12 lg:flex-row lg:items-center lg:gap-x-16 xl:gap-x-24"
			>
				<div class="lg:order-2">
					<img
						class="w-full rounded-lg object-cover shadow-lg dark:hidden"
						src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/case-study/agency-landing-page.jpg"
						alt=""
					/>
					<img
						class="hidden w-full rounded-lg object-cover shadow-lg dark:block"
						src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/case-study/agency-landing-page-dark.jpg"
						alt=""
					/>
				</div>

				<div class="w-full shrink-0 space-y-6 lg:order-1 lg:max-w-lg xl:max-w-2xl">
					<div class="space-y-3">
						<h3 class="text-3xl font-bold leading-tight text-gray-900 sm:text-4xl dark:text-white">
							Agency Landing Page
						</h3>
						<a
							href="https://themesberg.com"
							title=""
							class="inline-flex items-center text-lg font-medium text-primary-600 hover:underline dark:text-primary-500"
						>
							https://themesberg.com
							<svg
								aria-hidden="true"
								class="ml-2.5 h-5 w-5"
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 20 20"
								fill="currentColor"
							>
								<path
									d="M11 3a1 1 0 100 2h2.586l-6.293 6.293a1 1 0 101.414 1.414L15 6.414V9a1 1 0 102 0V4a1 1 0 00-1-1h-5z"
								/>
								<path
									d="M5 5a2 2 0 00-2 2v8a2 2 0 002 2h8a2 2 0 002-2v-3a1 1 0 10-2 0v3H5V7h3a1 1 0 000-2H5z"
								/>
							</svg>
						</a>
						<p class="text-base font-normal text-gray-500 sm:text-lg dark:text-gray-400">
							Flowbite helps you connect with friends, family and communities of people who share
							your interests. Connecting with your friends and family as well as discovering new
							ones is easy with features like Groups.
						</p>
					</div>

					<div class="flex items-center gap-2.5">
						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-wordpress"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/wordpress.svg"
								alt=""
							/>
						</div>

						<div
							id="tooltip-logo-wordpress"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							WordPress
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>

						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-html5"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/html5.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-html5"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							HTML5
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>

						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-css3"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/css-3.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-css3"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							CSS3
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>

						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-woocommerce"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/woocommerce.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-woocommerce"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							WooCommerce
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>
					</div>

					<a
						href="#"
						title=""
						class="inline-flex items-center justify-center rounded-lg bg-primary-700 px-5 py-2.5 text-center text-sm font-medium text-white hover:bg-primary-800 focus:outline-none focus:ring-4 focus:ring-primary-300 dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
						role="button"
					>
						View case study
						<svg
							aria-hidden="true"
							class="-mr-1 ml-2 h-5 w-5"
							xmlns="http://www.w3.org/2000/svg"
							viewBox="0 0 20 20"
							fill="currentColor"
						>
							<path
								fill-rule="evenodd"
								d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
								clip-rule="evenodd"
							/>
						</svg>
					</a>
				</div>
			</div>

			<div
				class="flex flex-col gap-y-8 sm:gap-y-12 lg:flex-row lg:items-center lg:gap-x-16 xl:gap-x-24"
			>
				<div>
					<img
						class="w-full rounded-lg object-cover shadow-lg dark:hidden"
						src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/case-study/mail-management-system.jpg"
						alt=""
					/>
					<img
						class="hidden w-full rounded-lg object-cover shadow-lg dark:block"
						src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/case-study/mail-management-system-dark.jpg"
						alt=""
					/>
				</div>

				<div class="w-full shrink-0 space-y-6 lg:max-w-lg xl:max-w-2xl">
					<div class="space-y-3">
						<h3 class="text-3xl font-bold leading-tight text-gray-900 sm:text-4xl dark:text-white">
							Mail management system
						</h3>
						<a
							href="https://ui.glass"
							title=""
							class="inline-flex items-center text-lg font-medium text-primary-600 hover:underline dark:text-primary-500"
						>
							https://ui.glass
							<svg
								aria-hidden="true"
								class="ml-2.5 h-5 w-5"
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 20 20"
								fill="currentColor"
							>
								<path
									d="M11 3a1 1 0 100 2h2.586l-6.293 6.293a1 1 0 101.414 1.414L15 6.414V9a1 1 0 102 0V4a1 1 0 00-1-1h-5z"
								/>
								<path
									d="M5 5a2 2 0 00-2 2v8a2 2 0 002 2h8a2 2 0 002-2v-3a1 1 0 10-2 0v3H5V7h3a1 1 0 000-2H5z"
								/>
							</svg>
						</a>
						<p class="text-base font-normal text-gray-500 sm:text-lg dark:text-gray-400">
							Flowbite helps you connect with friends, family and communities of people who share
							your interests. Connecting with your friends and family as well as discovering new
							ones is easy with features like Groups.
						</p>
					</div>

					<div class="flex items-center gap-2.5">
						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-typescript"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/typescript.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-typescript"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							TypeScript
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>

						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-java"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/java.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-java"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							Java
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>

						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-tailwind-css"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/tailwind-css.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-tailwind-css"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							Tailwind CSS
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>

						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-react"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/react.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-react"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							React
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>

						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-html5"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/html5.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-html5"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							HTML5
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>

						<div class="rounded-lg p-1 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-amazon-web-services"
								class="h-8 w-auto object-contain"
								src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/technologies/amazon-web-services.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-amazon-web-services"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							Amazon Web Services
							<div class="tooltip-arrow" data-popper-arrow></div>
						</div>
					</div>

					<a
						href="#"
						title=""
						class="inline-flex items-center justify-center rounded-lg bg-primary-700 px-5 py-2.5 text-center text-sm font-medium text-white hover:bg-primary-800 focus:outline-none focus:ring-4 focus:ring-primary-300 dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
						role="button"
					>
						View case study
						<svg
							aria-hidden="true"
							class="-mr-1 ml-2 h-5 w-5"
							xmlns="http://www.w3.org/2000/svg"
							viewBox="0 0 20 20"
							fill="currentColor"
						>
							<path
								fill-rule="evenodd"
								d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
								clip-rule="evenodd"
							/>
						</svg>
					</a>
				</div>
			</div>
		</div>
	</div>
</section>
<section id="contact">
	<div class="mx-auto max-w-screen-md px-4 py-8 lg:py-16">
		<h2
			class="mb-4 text-center text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white"
		>
			Contact Us
		</h2>
		<p class="mb-8 text-center font-light text-gray-500 sm:text-xl lg:mb-16 dark:text-gray-400">
			Got a technical issue? Want to send feedback about a beta feature? Need details about our
			Business plan? Let us know.
		</p>
		<form action="#" class="space-y-8">
			<div>
				<label for="email" class="mb-2 block text-sm font-medium text-gray-900 dark:text-gray-300"
					>Your email</label
				>
				<input
					type="email"
					id="email"
					class="block w-full rounded-lg border border-gray-300 bg-gray-50 p-2.5 text-sm text-gray-900 shadow-sm focus:border-primary-500 focus:ring-primary-500 dark:border-gray-600 dark:bg-gray-700 dark:text-white dark:placeholder-gray-400 dark:shadow-sm-light dark:focus:border-primary-500 dark:focus:ring-primary-500"
					placeholder="name@flowbite.com"
					required
				/>
			</div>
			<div>
				<label for="subject" class="mb-2 block text-sm font-medium text-gray-900 dark:text-gray-300"
					>Subject</label
				>
				<input
					type="text"
					id="subject"
					class="block w-full rounded-lg border border-gray-300 bg-gray-50 p-3 text-sm text-gray-900 shadow-sm focus:border-primary-500 focus:ring-primary-500 dark:border-gray-600 dark:bg-gray-700 dark:text-white dark:placeholder-gray-400 dark:shadow-sm-light dark:focus:border-primary-500 dark:focus:ring-primary-500"
					placeholder="Let us know how we can help you"
					required
				/>
			</div>
			<div class="sm:col-span-2">
				<label for="message" class="mb-2 block text-sm font-medium text-gray-900 dark:text-gray-400"
					>Your message</label
				>
				<textarea
					id="message"
					rows="6"
					class="block w-full rounded-lg border border-gray-300 bg-gray-50 p-2.5 text-sm text-gray-900 shadow-sm focus:border-primary-500 focus:ring-primary-500 dark:border-gray-600 dark:bg-gray-700 dark:text-white dark:placeholder-gray-400 dark:focus:border-primary-500 dark:focus:ring-primary-500"
					placeholder="Leave a comment..."
				></textarea>
			</div>
			<button
				type="submit"
				class="rounded-lg bg-primary-700 px-5 py-3 text-center text-sm font-medium text-white hover:bg-primary-800 focus:outline-none focus:ring-4 focus:ring-primary-300 sm:w-fit dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
				>Send message</button
			>
		</form>
	</div>
</section>
