<script>
	import { page } from '$app/stores';
	import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
	import logo from '$assets/logo.svg';
	$: activeUrl = $page.url.pathname;
</script>

<Navbar>
	<NavBrand href="/">
		<img src={logo} class="me-3 h-6 sm:h-9" alt="Portfolio Logo" />
		<span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white"
			>Karan Ravindra</span
		>
	</NavBrand>
	<NavHamburger />
	<NavUl {activeUrl}>
		<NavLi href="/">Home</NavLi>
		<NavLi href="/about">About</NavLi>
		<NavLi href="/blog">Blog</NavLi>
		<NavLi href="/project">Project</NavLi>
		<NavLi href="/contact">Contact</NavLi>
	</NavUl>
</Navbar>
