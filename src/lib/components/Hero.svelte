<script lang="ts">
	import { onMount } from 'svelte';
</script>

<section class="relative pt-32 pb-20 overflow-hidden bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="max-w-4xl">
			<h1 class="text-6xl md:text-7xl lg:text-[5.5rem] leading-[1.1] font-normal tracking-tight mb-8 text-red-500">
				Transform retail operations with <span class="italic font-light">custom AI</span>
			</h1>

			<p class="text-xl text-yellow-400 max-w-2xl mb-10 leading-relaxed font-light font-sans">
				Built by former Google technologists. Co-developed with your team. 
				AI solutions that understand retail workflows and drive real results.
			</p>

			<div class="flex flex-wrap gap-4 mb-20">
				<a href="mailto:info@mercatorintelligence.com" class="bg-white hover:bg-gray-200 text-black px-8 py-4 rounded-full font-medium transition-colors text-base inline-block">
					Get Started
				</a>
				<a href="#approach" class="bg-white/10 hover:bg-white/20 border border-white/10 text-white px-8 py-4 rounded-full font-medium transition-colors text-base inline-block">
					Our Approach
				</a>
			</div>
		</div>
	</div>

	<!-- Hero Image Container with Perspective -->
	<div class="relative w-full max-w-[1400px] mx-auto px-6 perspective-container">
		<div class="relative transform-3d hero-image-container origin-top opacity-90 hover:opacity-100 transition-opacity duration-700">
			<!-- Retail Analytics Dashboard Mockup -->
			<div class="rounded-xl overflow-hidden border border-gray-200 shadow-2xl bg-gray-50 aspect-[16/10] relative">
				<!-- Top bar -->
				<div class="h-10 bg-red-500 border-b border-gray-200 flex items-center px-4 gap-2">
                    <div class="flex gap-2">
                        <div class="w-3 h-3 rounded-full bg-red-500/30"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-500/30"></div>
                        <div class="w-3 h-3 rounded-full bg-green-500/30"></div>
                    </div>
                    <div class="mx-auto w-1/3 h-6 bg-gray-100 rounded-md text-[10px] flex items-center justify-center text-gray-500 font-mono">
                        Retail Intelligence Dashboard
                    </div>
				</div>
				<!-- Content Mockup -->
				<div class="flex h-full">
                    <!-- Sidebar -->
                    <div class="w-64 border-r border-gray-200 bg-white p-4 hidden md:block">
                        <div class="space-y-4">
                            <div class="h-8 w-full bg-gray-100 rounded flex items-center px-3 text-[10px] text-gray-700">Demand Forecast</div>
                            <div class="space-y-2 mt-8">
                                <div class="h-4 w-3/4 bg-gray-100 rounded opacity-50 flex items-center px-2 text-[8px] text-gray-500">Inventory</div>
                                <div class="h-4 w-1/2 bg-gray-100 rounded opacity-50 flex items-center px-2 text-[8px] text-gray-500">Pricing</div>
                                <div class="h-4 w-2/3 bg-gray-100 rounded opacity-50 flex items-center px-2 text-[8px] text-gray-500">Customer</div>
                            </div>
                        </div>
                    </div>
                    <!-- Main Content -->
                    <div class="flex-1 p-8 bg-gray-50">
                        <div class="flex justify-between items-end mb-8">
                            <div>
                                <div class="h-10 w-64 bg-white rounded mb-2 flex items-center px-4 text-sm text-gray-700 border border-gray-200">Q1 2025 Forecast</div>
                                <div class="h-4 w-48 bg-gray-100 rounded flex items-center px-3 text-[10px] text-gray-500">Updated 2 minutes ago</div>
                            </div>
                            <div class="h-10 w-32 bg-white rounded flex items-center justify-center text-[10px] text-gray-600 border border-gray-200">Export</div>
                        </div>
                        
                        <div class="grid grid-cols-3 gap-6 mb-8">
                            <div class="bg-white p-4 rounded-lg border border-gray-200 h-32 flex flex-col justify-between">
                                <div class="text-[10px] text-gray-500">Revenue Forecast</div>
                                <div class="text-2xl font-bold text-gray-900">$12.4M</div>
                                <div class="text-[10px] text-green-600">↗ 18.2%</div>
                            </div>
                            <div class="bg-white p-4 rounded-lg border border-gray-200 h-32 flex flex-col justify-between">
                                <div class="text-[10px] text-gray-500">Inventory Turn</div>
                                <div class="text-2xl font-bold text-gray-900">4.2x</div>
                                <div class="text-[10px] text-green-600">↗ 12%</div>
                            </div>
                            <div class="bg-white p-4 rounded-lg border border-gray-200 h-32 flex flex-col justify-between">
                                <div class="text-[10px] text-gray-500">Stock Accuracy</div>
                                <div class="text-2xl font-bold text-gray-900">94.8%</div>
                                <div class="text-[10px] text-green-600">↗ 8%</div>
                            </div>
                        </div>

                        <div class="bg-white rounded-lg border border-gray-200 h-64 w-full p-6 relative overflow-hidden">
                             <!-- Chart Mockup -->
                             <div class="absolute bottom-0 left-0 right-0 h-32 bg-gradient-to-t from-primary-500/10 to-transparent"></div>
                             <svg class="w-full h-full text-primary-400/50" viewBox="0 0 100 50" preserveAspectRatio="none">
                                 <path d="M0 50 L10 40 L20 45 L30 30 L40 35 L50 20 L60 25 L70 15 L80 20 L90 10 L100 5 V50 H0 Z" fill="currentColor" />
                             </svg>
                        </div>
                    </div>
                </div>

				<!-- Gradient Overlay -->
				<div class="absolute inset-0 bg-gradient-to-t from-gray-900/5 via-transparent to-transparent pointer-events-none"></div>
			</div>
		</div>
	</div>
    
    <!-- Credentials Banner -->
    <div class="max-w-[1400px] mx-auto px-6 mt-20">
        <div class="flex flex-wrap justify-center items-center gap-12 opacity-60">
            <div class="text-center">
                <div class="text-sm text-gray-500 mb-1">Founded by</div>
                <div class="text-lg font-medium text-gray-900">Google AI Leaders</div>
            </div>
            <div class="w-px h-12 bg-gray-200"></div>
            <div class="text-center">
                <div class="text-sm text-gray-500 mb-1">Alumni of</div>
                <div class="text-lg font-medium text-gray-900">Stanford University</div>
            </div>
            <div class="w-px h-12 bg-gray-200"></div>
            <div class="text-center">
                <div class="text-sm text-gray-500 mb-1">Experience from</div>
                <div class="text-lg font-medium text-gray-900">Google X Moonshot Factory</div>
            </div>
        </div>
    </div>
</section>

<style>
	.perspective-container {
		perspective: 2000px;
	}
	.transform-3d {
		transform: rotateX(20deg) scale(0.9);
        transform-style: preserve-3d;
	}
</style>
