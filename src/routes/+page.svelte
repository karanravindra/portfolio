<script lang="ts">
	import img from '$assets/3d-casual-life-young-man-at-workplace-with-coffee.png';
	import { Button } from 'flowbite-svelte';
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

			<Button color="primary" size="lg" class="mr-3 mt-4"
				>Primary Button
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
				></Button
			>
			<Button color="light" size="lg" class="mt-4">Secondary Button</Button>
		</div>
		<div class="hidden lg:col-span-5 lg:mt-0 lg:flex">
			<img src={img} alt="illustration of a person in a chair from Icons8" />
		</div>
	</div>
</section>
<section id="about">
	<div class="mx-auto max-w-screen-xl px-4 py-8 sm:py-16 lg:px-6">
		<h2 class="mb-4 text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white">
			About me
		</h2>
		<div class="flex flex-row space-x-4">
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
			<Button color="light" size="lg"
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
				<article>
					<div class="space-y-3">
						<span
							class="inline-flex items-center rounded bg-indigo-100 px-2.5 py-0.5 text-xs font-medium text-indigo-800 dark:bg-indigo-900 dark:text-indigo-300"
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
									d="M4 4a2 2 0 012-2h4.586A2 2 0 0112 2.586L15.414 6A2 2 0 0116 7.414V16a2 2 0 01-2 2H6a2 2 0 01-2-2V4zm2 6a1 1 0 011-1h6a1 1 0 110 2H7a1 1 0 01-1-1zm1 3a1 1 0 100 2h6a1 1 0 100-2H7z"
									clip-rule="evenodd"
								/>
							</svg>
							Tutorial
						</span>

						<h2
							class="text-2xl font-bold leading-tight tracking-tight text-gray-900 dark:text-white"
						>
							<a href="#" class="hover:underline" title="">
								How to rank higher on Google (6 easy steps)
							</a>
						</h2>

						<p class="text-base font-normal text-gray-500 dark:text-gray-400">
							Static websites are now used to bootstrap lots of websites and are becoming the basis
							for a variety of tools that even influence both web designers and developers.
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

				<article>
					<div class="space-y-3">
						<span
							class="inline-flex items-center rounded bg-pink-100 px-2.5 py-0.5 text-xs font-medium text-pink-800 dark:bg-pink-900 dark:text-pink-300"
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
									d="M7 4a3 3 0 016 0v4a3 3 0 11-6 0V4zm4 10.93A7.001 7.001 0 0017 8a1 1 0 10-2 0A5 5 0 015 8a1 1 0 00-2 0 7.001 7.001 0 006 6.93V17H6a1 1 0 100 2h8a1 1 0 100-2h-3v-2.07z"
									clip-rule="evenodd"
								/>
							</svg>
							Interview
						</span>

						<h2
							class="text-2xl font-bold leading-tight tracking-tight text-gray-900 dark:text-white"
						>
							<a href="#" class="hover:underline" title="">
								How to schedule your tweets to send later
							</a>
						</h2>

						<p class="text-base font-normal text-gray-500 dark:text-gray-400">
							Static websites are now used to bootstrap lots of websites and are becoming the basis
							for a variety of tools that even.
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

				<article>
					<div class="space-y-3">
						<span
							class="inline-flex items-center rounded bg-green-100 px-2.5 py-0.5 text-xs font-medium text-green-800 dark:bg-green-900 dark:text-green-300"
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
									d="M18 3a1 1 0 00-1.447-.894L8.763 6H5a3 3 0 000 6h.28l1.771 5.316A1 1 0 008 18h1a1 1 0 001-1v-4.382l6.553 3.276A1 1 0 0018 15V3z"
									clip-rule="evenodd"
								/>
							</svg>
							Marketing
						</span>

						<h2
							class="text-2xl font-bold leading-tight tracking-tight text-gray-900 dark:text-white"
						>
							<a href="#" class="hover:underline" title="">
								12 SEO best practices that everyone should follow
							</a>
						</h2>

						<p class="text-base font-normal text-gray-500 dark:text-gray-400">
							Static websites are now used to bootstrap lots of websites and are becoming the basis.
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
				My projects
			</h2>
			<p class="mt-4 text-base font-normal text-gray-500 sm:text-xl dark:text-gray-400">
				Here are just a few of the projects I've worked on.
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
							My Personal Portfolio
						</h3>
						<a
							href="https://karanravindra.me"
							title=""
							class="inline-flex items-center text-lg font-medium text-primary-600 hover:underline dark:text-primary-500"
						>
							https://karanravindra.me
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
							My personal portfolio is a showcase of my work, my thoughts and my journey. It's a
							place where I can share my thoughts and ideas with the world. It's a place where I can
							connect with people who share my interests.
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
		</div>
	</div>
</section>
<section id="contact">
	<div class="mx-auto max-w-screen-md px-4 py-8 lg:py-16">
		<h2
			class="mb-4 text-center text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white"
		>
			Get in touch
		</h2>
		<p class="mb-8 text-center font-light text-gray-500 sm:text-xl lg:mb-16 dark:text-gray-400">
			Have a question or want to work together? I'd love to hear from you. Send me a message and
			I'll respond as soon as possible.
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
