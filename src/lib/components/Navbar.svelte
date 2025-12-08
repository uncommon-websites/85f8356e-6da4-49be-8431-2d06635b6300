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
		<a href="/" class="text-2xl font-serif tracking-tight font-medium">Sana</a>

		<!-- Desktop Links -->
		<div class="hidden lg:flex items-center gap-8 text-sm font-medium text-gray-300">
			<a href="#" class="hover:text-white transition-colors">Sana Agents</a>
			<a href="#" class="hover:text-white transition-colors">Solutions</a>
			<a href="#" class="hover:text-white transition-colors">Integrations</a>
			<a href="#" class="hover:text-white transition-colors">Security</a>
			<a href="#" class="hover:text-white transition-colors">Events</a>
			<a href="#" class="hover:text-white transition-colors">Stories</a>
			<a href="#" class="hover:text-white transition-colors">Pricing</a>
		</div>

		<!-- Right Actions -->
		<div class="hidden lg:flex items-center gap-6">
			<a href="#" class="text-sm font-medium text-white hover:text-gray-300 transition-colors">Log in</a>
			<a href="#" class="bg-[#3b82f6] hover:bg-blue-600 text-white px-5 py-2.5 rounded-full text-sm font-medium transition-colors">
				Book a demo
			</a>
		</div>

		<!-- Mobile Menu Button -->
		<button class="lg:hidden text-white" onclick={toggleMenu}>
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
			<a href="#" class="text-lg font-medium text-gray-300 hover:text-white">Sana Agents</a>
			<a href="#" class="text-lg font-medium text-gray-300 hover:text-white">Solutions</a>
			<a href="#" class="text-lg font-medium text-gray-300 hover:text-white">Integrations</a>
			<a href="#" class="text-lg font-medium text-gray-300 hover:text-white">Security</a>
			<a href="#" class="text-lg font-medium text-gray-300 hover:text-white">Events</a>
			<a href="#" class="text-lg font-medium text-gray-300 hover:text-white">Stories</a>
			<a href="#" class="text-lg font-medium text-gray-300 hover:text-white">Pricing</a>
			<div class="h-px bg-white/10 my-2"></div>
			<a href="#" class="text-lg font-medium text-white">Log in</a>
			<a href="#" class="bg-[#3b82f6] text-white px-5 py-3 rounded-full text-center font-medium">
				Book a demo
			</a>
		</div>
	{/if}
</nav>
