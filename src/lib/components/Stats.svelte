<script lang="ts">
	import { ArrowLeft, ArrowRight } from 'lucide-svelte';
</script>

<section class="py-20 bg-black text-white border-t border-white/5">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 lg:gap-12">
			<!-- Stat 1 -->
			<div class="flex flex-col h-full justify-between group cursor-pointer">
				<p class="text-sm text-gray-400 mb-8 leading-relaxed">
					Global law firm automates compiling and analysis of legal docs
				</p>
				<div>
					<div class="text-5xl md:text-6xl font-normal mb-2 tracking-tight">62%</div>
					<div class="flex items-center gap-2">
						<div class="w-2 h-2 rounded-full bg-green-500"></div>
						<span class="text-xs font-semibold tracking-wider text-gray-400 uppercase">Time Savings</span>
					</div>
				</div>
			</div>

			<!-- Stat 2 -->
			<div class="flex flex-col h-full justify-between group cursor-pointer">
				<p class="text-sm text-gray-400 mb-8 leading-relaxed">
					European fintech scales up uses AI agent for new hire onboarding
				</p>
				<div>
					<div class="text-5xl md:text-6xl font-normal mb-2 tracking-tight">10h</div>
					<div class="flex items-center gap-2">
						<div class="w-2 h-2 rounded-full bg-green-500"></div>
						<span class="text-xs font-semibold tracking-wider text-gray-400 uppercase">Per Week/Employee Saved</span>
					</div>
				</div>
			</div>

			<!-- Stat 3 -->
			<div class="flex flex-col h-full justify-between group cursor-pointer">
				<p class="text-sm text-gray-400 mb-8 leading-relaxed">
					Leading Swedish mining manufacturer automates R&D analysis workflows
				</p>
				<div>
					<div class="text-5xl md:text-6xl font-normal mb-2 tracking-tight">50%</div>
					<div class="flex items-center gap-2">
						<div class="w-2 h-2 rounded-full bg-green-500"></div>
						<span class="text-xs font-semibold tracking-wider text-gray-400 uppercase">Time Savings</span>
					</div>
				</div>
			</div>

			<!-- Stat 4 -->
			<div class="flex flex-col h-full justify-between group cursor-pointer">
				<p class="text-sm text-gray-400 mb-8 leading-relaxed">
					Industrial market leader uses AI agent to augment customer support
				</p>
				<div>
					<div class="text-5xl md:text-6xl font-normal mb-2 tracking-tight">2x</div>
					<div class="flex items-center gap-2">
						<div class="w-2 h-2 rounded-full bg-green-500"></div>
						<span class="text-xs font-semibold tracking-wider text-gray-400 uppercase">Number of Issues Resolved</span>
					</div>
				</div>
			</div>
		</div>

        <!-- Navigation Buttons -->
        <div class="flex justify-end gap-2 mt-12">
            <button class="w-10 h-10 rounded-full bg-white/5 hover:bg-white/10 flex items-center justify-center transition-colors">
                <ArrowLeft size={16} />
            </button>
            <button class="w-10 h-10 rounded-full bg-white/5 hover:bg-white/10 flex items-center justify-center transition-colors">
                <ArrowRight size={16} />
            </button>
        </div>
	</div>
</section>
