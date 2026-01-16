<script lang="ts">
    import { Play } from 'lucide-svelte';
</script>

<section class="py-24 bg-white text-gray-900">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="text-center mb-20">
			<h2 class="text-4xl md:text-5xl lg:text-6xl font-normal mb-6">
				Custom AI solutions<br />
				for retail operations
			</h2>
			<p class="text-gray-400 text-lg max-w-2xl mx-auto">
				Co-developed intelligence that understands your workflows, integrates with your systems, and drives measurable results.
			</p>
		</div>

		<!-- Row 1 -->
		<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
			<!-- Card 1: Demand Forecasting -->
			<div class="bg-gray-50 rounded-xl p-8 border border-gray-200 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Demand Forecasting</h3>
					<p class="text-gray-600 text-sm">Predict customer demand with precision across channels and categories</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative bg-white rounded-lg border border-gray-200 overflow-hidden p-6 flex flex-col">
                    <!-- Top stats row -->
                    <div class="flex gap-4 mb-6">
                        <div class="bg-primary-500/10 p-4 r-4 rounded w-1/3 border border-primary-500/20">
                            <div class="text-xs text-primary-300 mb-1">Next Week</div>
                            <div class="text-xl font-bold text-primary-400">+18% ↗</div>
                        </div>
                         <div class="bg-white/5 p-4 rounded w-1/3 border border-white/10">
                            <div class="text-xs text-gray-400 mb-1">Accuracy</div>
                            <div class="text-xl font-bold text-white">92%</div>
                        </div>
                         <div class="bg-white/5 p-4 rounded w-1/3 border border-white/10">
                            <div class="text-xs text-gray-400 mb-1">Confidence</div>
                            <div class="text-xl font-bold text-white">High</div>
                        </div>
                    </div>
                    
                    <!-- Chart -->
                    <div class="flex-1 w-full relative mt-4">
                         <svg class="w-full h-full overflow-visible" viewBox="0 0 100 50" preserveAspectRatio="none">
                             <!-- Grid lines -->
                             <line x1="0" y1="10" x2="100" y2="10" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             <line x1="0" y1="25" x2="100" y2="25" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             <line x1="0" y1="40" x2="100" y2="40" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             
                             <!-- Lines -->
                             <path d="M0 45 C 20 40, 40 30, 60 25 S 80 15, 100 5" fill="none" stroke="oklch(0.696 0.17 162.48)" stroke-width="2" />
                             <path d="M0 48 C 20 45, 40 40, 60 38 S 80 35, 100 30" fill="none" stroke="#666" stroke-width="1" stroke-dasharray="3 3" />
                             
                             <!-- Area under curve -->
                             <path d="M0 48 C 20 45, 40 40, 60 38 S 80 35, 100 30 V 50 H 0 Z" fill="oklch(0.696 0.17 162.48)" fill-opacity="0.1" />
                         </svg>
                    </div>
                </div>
			</div>

			<!-- Card 2: Inventory Optimization -->
			<div class="bg-gray-50 rounded-xl p-8 border border-gray-200 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Inventory Optimization</h3>
					<p class="text-gray-600 text-sm">Optimize stock levels and allocation across your entire network</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative">
                    <div class="absolute inset-0 flex items-center justify-center">
                         <!-- Inventory visualization -->
                         <div class="w-full h-full border border-white/5 rounded-lg bg-[#0a0a0a] p-6 space-y-3">
                             <div class="flex items-center justify-between p-3 bg-white/5 rounded">
                                 <div class="text-xs text-gray-400">Store A</div>
                                 <div class="flex-1 mx-4 h-2 bg-white/10 rounded-full overflow-hidden">
                                     <div class="h-full ary-500 w-[85%]"></div>
                                 </div>
                                 <div class="text-xs text-white">85%</div>
                             </div>
                             <div class="flex items-center justify-between p-3 bg-white/5 rounded">
                                 <div class="text-xs text-gray-400">Store B</div>
                                 <div class="flex-1 mx-4 h-2 bg-white/10 rounded-full overflow-hidden">
                                     <div class="h-full bg-primary-500 w-[62%]"></div>
                                 </div>
                                 <div class="text-xs text-white">62%</div>
                             </div>
                             <div class="flex items-center justify-between p-3 bg-white/5 rounded">
                                 <div class="text-xs text-gray-400">Store C</div>
                                 <div class="flex-1 mx-4 h-2 bg-white/10 rounded-full overflow-hidden">
                                     <div class="h-full bg-yellow-500 w-[95%]"></div>
                                 </div>
                                 <div class="text-xs text-yellow-400">95%</div>
                             </div>
                             <div class="flex items-center justify-between p-3 bg-white/5 rounded">
                                 <div class="text-xs text-gray-400">Store D</div>
                                 <div class="flex-1 mx-4 h-2 bg-white/10 rounded-full overflow-hidden">
                                     <div class="h-full bg-primary-500 w-[78%]"></div>
                                 </div>
                                 <div class="text-xs text-white">78%</div>
                             </div>
                             <div class="mt-6 p-4 bg-primary-500/10 border border-primary-500/20 rounded text-xs text-primary-300">
                                 Recommendation: Transfer 120 units from Store C to Store B
                             </div>
                         </div>
                    </div>
                </div>
			</div>
		</div>

        <!-- Row 2 -->
		<div class="grid grid-cols-1 md:grid-cols-3 gap-6">
			<!-- Card 3: Customer Intelligence -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Customer Intelligence</h3>
					<p class="text-gray-400 text-sm">Uncover insights from transaction and behavior data</p>
				</div>
                
                 <!-- Mockup Content- Insights -->
                <div class="flex-1 relative bg-white rounded-lg border border-gray-200 overflow-hidden p-4 space-y-3">
                    <div class="p-3 bg-gray-50 rounded border-l-2 border-primary-500">
                        <div class="text-[10px] text-gray-500 mb-1">SEGMENT INSIGHT</div>
                        <div class="text-xs text-gray-900">High-value customers prefer weekend shopping</div>
                    </div>
                    <div class="p-3 bg-gray-50 rounded border-l-2 border-primary-500">
                        <div class="text-[10px] text-gray-500 mb-1">TREND ALERT</div>
                        <div class="text-xs text-gray-900">Athleisure category up 24% this month</div>
                    </div>
                    <div class="p-3 bg-gray-50 rounded border-l-2 border-yellow-500">
                        <div class="text-[10px] text-gray-500 mb-1">CHURN RISK</div>
                        <div class="text-xs text-gray-900">156 customers at risk - recommend outreach</div>
                    </div>
                    <div class="p-3 bg-gray-50 rounded border-l-2 border-primary-500">
                        <div class="text-[10px] text-gray-500 mb-1">OPPORTUNITY</div>
                        <div class="text-xs text-gray-900">Cross-sell potential: $2.4M in accessories</div>
                    </div>
                </div>
			</div>

			<!-- Card 4: Pricing Intelligence -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Pricing Intelligence</h3>
					<p class="text-gray-400 text-sm">Optimize pricing strategy with competitive insights</p>
				</div>
                
                 <!-- Mockup Content - Pricing Grid -->
                <div class="flex-1 relative flex items-center justify-center">
                    <div class="w-full space-y-4">
                        <div class="bg-[#1a1a1a] border border-white/10 rounded-lg p-4">
                            <div class="flex justify-between items-center mb-2">
                                <div class="text-xs text-gray-400">Product SKU-1234</div>
                                <div class="text-xs text-primary-400">Optimal</div>
                            </div>
                            <div class="flex items-baseline gap-2">
                                <div class="text-2xl font-bold text-white">$49.99</div>
                                <div class="text-xs text-gray-500 line-through">$54.99</div>
                            </div>
                            <div class="mt-2 text-[10px] text-gray-500">Market avg: $51.20</div>
                        </div>
                        
                        <div class="bg-[#1a1a1a] border border-yellow-500/30 rounded-lg p-4">
                            <div class="flex justify-between items-center mb-2">
                                <div class="text-xs text-gray-400">Product SKU-5678</div>
                                <div class="text-xs text-yellow-400">Review</div>
                            </div>
                            <div class="flex items-baseline gap-2">
                                <div class="text-2xl font-bold text-white">$89.99</div>
                                <div class="text-xs text-yellow-400">→ $84.99</div>
                            </div>
                            <div class="mt-2 text-[10px] text-gray-500">Market avg: $82.50</div>
                        </div>
                    </div>
                </div>
			</div>

            <!-- Card 5: Workflow Integration -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Workflow Integration</h3>
					<p class="text-gray-400 text-sm">Seamlessly integrate with your existing systems</p>
				</div>
                
                 <!-- Mockup Content - Integration Flow -->
                <div class="flex-1 relative flex flex-col gap-4 items-center justify-center">
                    <div class="flex items-center gap-3 w-full">
                        <div class="flex-1 bg-white/5 rounded p-3 text-center border border-white/10">
                            <div class="text-[10px] text-gray-400">ERP System</div>
                        </div>
                        <div class="text-gray-600">→</div>
                        <div class="flex-1 bg-primary-500/10 rounded p-3 text-center border border-primary-500/20">
                            <div class="text-[10px] text-primary-300">Mercator AI</div>
                        </div>
                    </div>
                    
                    <div class="flex items-center gap-3 w-full">
                        <div class="flex-1 bg-white/5 rounded p-3 text-center border border-white/10">
                            <div class="text-[10px] text-gray-400">POS Data</div>
                        </div>
                        <div class="text-gray-600">→</div>
                        <div class="flex-1 bg-primary-500/10 rounded p-3 text-center border border-primary-500/20">
                            <div class="text-[10px] text-primary-300">Mercator AI</div>
                        </div>
                    </div>
                    
                    <div class="flex items-center gap-3 w-full">
                        <div class="flex-1 bg-gray-100 rounded p-3 text-center border border-gray-200">
                            <div class="text-[10px] text-gray-600">E-commerce</div>
                        </div>
                        <div class="text-gray-400">→</div>
                        <div class="flex-1 bg-primary-50 rounded p-3 text-center border border-primary-200">
                            <div class="text-[10px] text-primary-700">Mercator AI</div>
                        </div>
                    </div>
                    
                    <div class="mt-4 text-center">
                        <div class="text-[10px] text-gray-500">Real-time data synchronization</div>
                    </div>
                </div>
			</div>
		</div>
	</div>
</section>
ction>
