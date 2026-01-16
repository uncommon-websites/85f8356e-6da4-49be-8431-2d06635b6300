<script lang="ts">
	import { Menu, X } from 'lucide-svelte';
    import { onMount } from 'svelte';

	let isMenuOpen = false;
    let isScrolled = false;

    function toggleMenu() {
        isMenuOpen = !isMenuOpen;
    }

    onMount(() => {
        const handleScroll = () => {
            isScrolled = window.scrollY > 20;
        };
        window.addEventListener('scroll', handleScroll);
        return () => window.removeEventListener('scroll', handleScroll);
    });
</script>

<nav class="fixed top-0 left-0 w-full z-50 transition-all duration-300 {isScrolled ? 'bg-black/80 backdrop-blur-md border-b border-white/10' : 'bg-transparent'} text-white">
	<div class="max-w-[1400px] mx-auto px-6 h-20 flex items-center justify-between">
		<!-- Logo -->
		<a href="/" class="flex items-center gap-3">
			<svg width="32" height="35" viewBox="0 0 97 105" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path opacity="0.5" d="M0.84375 29.5892V75.3785L43.791 45.7896V0L0.84375 29.5892Z" fill="white"/>
				<path opacity="0.5" d="M0.84375 75.3787V29.5891L43.791 59.1783V104.968L0.84375 75.3787Z" fill="white"/>
				<path opacity="0.5" d="M96.8438 29.5891V75.3787L53.8965 45.7895V0L96.8438 29.5891Z" fill="white"/>
				<path opacity="0.5" d="M96.8438 75.3787V29.5891L53.8965 59.1783V104.968L96.8438 75.3787Z" fill="white"/>
			</svg>
			<span class="text-lg font-medium tracking-tight">Mercator Intelligence</span>
		</a>

		<!-- Desktop Links -->
		<div class="hidden lg:flex items-center gap-8 text-sm font-medium text-gray-600">
			<a href="#solutions" class="hover:text-gray-900 transition-colors">Solutions</a>
			<a href="#industries" class="hover:text-gray-900 transition-colors">Industries</a>
			<a href="#team" class="hover:text-gray-900 transition-colors">Team</a>
			<a href="#approach" class="hover:text-gray-900 transition-colors">Approach</a>
		</div>

		<!-- Right Actions -->
		<div class="hidden lg:flex items-center gap-6">
			<a href="mailto:info@mercatorintelligence.com" class="bg-gray-900 hover:bg-gray-800 text-white px-5 py-2.5 rounded-full text-sm font-medium transition-colors">
				Get Started
			</a>
		</div>

		<!-- Mobile Menu Button -->
		<button class="lg:hidden text-gray-900" onclick={toggleMenu}>
			{#if isMenuOpen}
				<X size={24} />
			{:else}
				<Menu size={24} />
			{/if}
		</button>
	</div>

	<!-- Mobile Menu -->
	{#if isMenuOpen}
		<div class="lg:hidden bg-black absolute top-20 left-0 w-full h-[calc(100vh-80px)] p-6 flex flex-col gap-6 overflow-y-auto border-t border-white/10">
			<a href="#solutions" class="text-lg font-medium text-gray-300 hover:text-white">Solutions</a>
			<a href="#industries" class="text-lg font-medium text-gray-300 hover:text-white">Industries</a>
			<a href="#team" class="text-lg font-medium text-gray-300 hover:text-white">Team</a>
			<a href="#approach" class="text-lg font-medium text-gray-300 hover:text-white">Approach</a>
			<div class="h-px bg-white/10 my-2"></div>
			<a href="mailto:info@mercatorintelligence.com" class="bg-white text-black px-5 py-3 rounded-full text-center font-medium">
				Get Started
			</a>
		</div>
	{/if}
</nav>
