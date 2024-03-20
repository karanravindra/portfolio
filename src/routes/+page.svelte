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
	<div class="mx-auto max-w-screen-xl px-4 py-8 lg:px-6 lg:py-16">
		<div class="mx-auto mb-8 max-w-screen-sm text-center lg:mb-16">
			<h2
				class="mb-4 text-3xl font-extrabold tracking-tight text-gray-900 lg:text-4xl dark:text-white"
			>
				Our Blog
			</h2>
			<p class="font-light text-gray-500 sm:text-xl dark:text-gray-400">
				We use an agile approach to test assumptions and connect with the needs of your audience
				early and often.
			</p>
		</div>
		<div class="grid gap-8 lg:grid-cols-3">
			<article
				class="rounded-lg border border-gray-200 bg-white p-6 shadow-md dark:border-gray-700 dark:bg-gray-800"
			>
				<div class="mb-5 flex items-center justify-between text-gray-500">
					<span
						class="inline-flex items-center rounded bg-primary-100 px-2.5 py-0.5 text-xs font-medium text-primary-800 dark:bg-primary-200 dark:text-primary-800"
					>
						<svg
							class="mr-1 h-3 w-3"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								d="M2 6a2 2 0 012-2h6a2 2 0 012 2v8a2 2 0 01-2 2H4a2 2 0 01-2-2V6zM14.553 7.106A1 1 0 0014 8v4a1 1 0 00.553.894l2 1A1 1 0 0018 13V7a1 1 0 00-1.447-.894l-2 1z"
							></path></svg
						>
						Tutorial
					</span>
					<span class="text-sm">14 days ago</span>
				</div>
				<h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
					<a href="#">How to quickly deploy a static website</a>
				</h2>
				<p class="mb-5 font-light text-gray-500 dark:text-gray-400">
					Static websites are now used to bootstrap lots of websites and are becoming the basis for
					a variety of tools that even influence both web designers and developers influence both
					web designers and developers.
				</p>
			</article>
			<article
				class="rounded-lg border border-gray-200 bg-white p-6 shadow-md dark:border-gray-700 dark:bg-gray-800"
			>
				<div class="mb-5 flex items-center justify-between text-gray-500">
					<span
						class="inline-flex items-center rounded bg-primary-100 px-2.5 py-0.5 text-xs font-medium text-primary-800 dark:bg-primary-200 dark:text-primary-800"
					>
						<svg
							class="mr-1 h-3 w-3"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M2 5a2 2 0 012-2h8a2 2 0 012 2v10a2 2 0 002 2H4a2 2 0 01-2-2V5zm3 1h6v4H5V6zm6 6H5v2h6v-2z"
								clip-rule="evenodd"
							></path><path d="M15 7h1a2 2 0 012 2v5.5a1.5 1.5 0 01-3 0V7z"></path></svg
						>
						Article
					</span>
					<span class="text-sm">14 days ago</span>
				</div>
				<h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
					<a href="#">Our first project with React</a>
				</h2>
				<p class="mb-5 font-light text-gray-500 dark:text-gray-400">
					Static websites are now used to bootstrap lots of websites and are becoming the basis for
					a variety of tools that even influence both web designers and developers influence both
					web designers and developers.
				</p>
			</article>
			<article
				class="rounded-lg border border-gray-200 bg-white p-6 shadow-md dark:border-gray-700 dark:bg-gray-800"
			>
				<div class="mb-5 flex items-center justify-between text-gray-500">
					<span
						class="inline-flex items-center rounded bg-primary-100 px-2.5 py-0.5 text-xs font-medium text-primary-800 dark:bg-primary-200 dark:text-primary-800"
					>
						<svg
							class="mr-1 h-3 w-3"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M2 5a2 2 0 012-2h8a2 2 0 012 2v10a2 2 0 002 2H4a2 2 0 01-2-2V5zm3 1h6v4H5V6zm6 6H5v2h6v-2z"
								clip-rule="evenodd"
							></path><path d="M15 7h1a2 2 0 012 2v5.5a1.5 1.5 0 01-3 0V7z"></path></svg
						>
						Article
					</span>
					<span class="text-sm">14 days ago</span>
				</div>
				<h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
					<a href="#">Our first project with React</a>
				</h2>
				<p class="mb-5 font-light text-gray-500 dark:text-gray-400">
					Static websites are now used to bootstrap lots of websites and are becoming the basis for
					a variety of tools that even influence both web designers and developers influence both
					web designers and developers.
				</p>
			</article>
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
				Crafted with skill and care to help our clients grow their business!
			</p>
		</div>

		<div
			class="mt-12 grid grid-cols-1 gap-x-20 gap-y-12 text-center sm:mt-16 sm:grid-cols-2 lg:grid-cols-3"
		>
			<div class="space-y-4">
				<span
					class="inline-flex items-center rounded bg-gray-100 px-2.5 py-0.5 text-xs font-medium text-gray-900 dark:bg-gray-700 dark:text-gray-300"
				>
					Alphabet Inc.
				</span>
				<h3 class="text-2xl font-bold leading-tight text-gray-900 dark:text-white">
					Official website
				</h3>
				<p class="text-lg font-normal text-gray-500 dark:text-gray-400">
					Flowbite helps you connect with friends, family and communities of people who share your
					interests.
				</p>
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

			<div class="space-y-4">
				<span
					class="inline-flex items-center rounded bg-gray-100 px-2.5 py-0.5 text-xs font-medium text-gray-900 dark:bg-gray-700 dark:text-gray-300"
				>
					Microsoft Corp.
				</span>
				<h3 class="text-2xl font-bold leading-tight text-gray-900 dark:text-white">
					Management system
				</h3>
				<p class="text-lg font-normal text-gray-500 dark:text-gray-400">
					Flowbite helps you connect with friends, family and communities of people who share your
					interests.
				</p>
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

			<div class="space-y-4">
				<span
					class="inline-flex items-center rounded bg-gray-100 px-2.5 py-0.5 text-xs font-medium text-gray-900 dark:bg-gray-700 dark:text-gray-300"
				>
					Adobe Inc.
				</span>
				<h3 class="text-2xl font-bold leading-tight text-gray-900 dark:text-white">Logo design</h3>
				<p class="text-lg font-normal text-gray-500 dark:text-gray-400">
					Flowbite helps you connect with friends, family and communities of people who share your
					interests.
				</p>
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
