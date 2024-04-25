<script lang="ts">
	import img from '$assets/3d-casual-life-young-man-at-workplace-with-coffee.png?enhanced';
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
				>About Me
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
			<Button color="light" size="lg" class="mt-4">My Projects</Button>
		</div>
		<div class="hidden lg:col-span-5 lg:mt-0 lg:flex">
			<enhanced:img src={img} alt="illustration of a person in a chair from Icons8" />
		</div>
	</div>
</section>
