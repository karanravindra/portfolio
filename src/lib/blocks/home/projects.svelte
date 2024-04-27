<script lang="ts">
	import { Button } from 'flowbite-svelte';
</script>

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
			<!-- Project 1 -->
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
							This portfolio not only showcases my capabilities but also serves as a platform where
							I share my insights and creative ideas with a broader audience. Understanding the
							technologies and design choices I used will provide valuable insights into the
							complexity and creativity involved in developing a professional portfolio.
						</p>
					</div>

					<div class="flex items-center gap-2.5">
						<div class="rounded-lg p-2 hover:bg-gray-50 dark:hover:bg-gray-800">
							<img
								data-tooltip-target="tooltip-logo-svelte"
								class="h-6 w-auto object-contain"
								src="https://upload.wikimedia.org/wikipedia/commons/1/1b/Svelte_Logo.svg"
								alt=""
							/>
						</div>
						<div
							id="tooltip-logo-svelte"
							role="tooltip"
							class="tooltip invisible absolute z-10 inline-block rounded-lg bg-gray-900 px-3 py-2 text-sm font-medium text-white opacity-0 shadow-sm transition-opacity duration-300 dark:bg-gray-700"
						>
							Svelte
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

					<Button color="primary" size="md" class="mt-4" href="/blog/projects/portfolio-study"
						>View case study <svg
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
						</svg></Button
					>
				</div>
			</div>
			<!-- Project 2 -->
			<!-- <div
				class="flex flex-col gap-y-8 sm:gap-y-12 lg:flex-row lg:items-center lg:gap-x-16 xl:gap-x-24"
			>
				<div class="lg:order-2">
					<enhanced:img 
						class="w-full rounded-lg object-cover shadow-lg dark:hidden"
						src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/case-study/agency-landing-page.jpg"
						alt=""
					/>
					<enhanced:img 
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
							<enhanced:img 
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
							<enhanced:img 
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
							<enhanced:img 
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
							<enhanced:img 
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
			</div> -->
		</div>
	</div>
</section>
