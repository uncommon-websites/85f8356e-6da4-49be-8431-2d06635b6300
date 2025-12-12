<script lang="ts">
    import { Paperclip, Image, AtSign, Smile, ArrowUp } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white" id="team">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
			<div>
				<h2 class="text-4xl md:text-5xl lg:text-6xl font-normal mb-12 leading-tight">
					World-class technologists,<br />
					<span class="italic font-light">fluent in your workflows</span>
				</h2>

				<div class="space-y-8">
					<div>
						<div class="flex items-center gap-3 text-white font-medium mb-3">
							<div class="w-2 h-2 bg-primary-500 rounded-sm"></div>
							Google AI Leadership
						</div>
						<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1">
							Our founding team spent over a decade leading AI initiatives at Google, bringing enterprise-scale expertise to retail challenges.
						</p>
					</div>

					<div>
						<div class="flex items-center gap-3 text-white font-medium mb-3">
							<div class="w-2 h-2 bg-primary-500 rounded-sm"></div>
							Moonshot Factory Alumni
						</div>
						<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1">
							Experience from Google X Development, where we learned to tackle ambitious problems with innovative AI solutions.
						</p>
					</div>

					<div>
						<div class="flex items-center gap-3 text-white font-medium mb-3">
							<div class="w-2 h-2 bg-primary-500 rounded-sm"></div>
							Stanford Credentials
						</div>
						<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1">
							Deep academic foundations in artificial intelligence and machine learning from one of the world's leading institutions.
						</p>
					</div>

					<div>
						<div class="flex items-center gap-3 text-white font-medium mb-3">
							<div class="w-2 h-2 bg-primary-500 rounded-sm"></div>
							Retail Fluency
						</div>
						<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1">
							We don't just build AI—we understand retail operations, margins, inventory dynamics, and customer behavior.
						</p>
					</div>
				</div>
			</div>

			<div class="relative">
                <div class="rounded-xl overflow-hidden aspect-square relative bg-gradient-to-br from-gray-900 to-black border border-white/10">
                     <!-- Team visualization placeholder -->
                     <div class="absolute inset-0 flex items-center justify-center p-12">
                         <div class="w-full h-full relative">
                             <!-- Google logo reference -->
                             <div class="absolute top-0 left-0 right-0 text-center p-8 bg-white/5 rounded-lg border border-white/10">
                                 <div class="text-sm text-gray-500 mb-2">Previously at</div>
                                 <div class="text-3xl font-bold text-white">Google</div>
                                 <div class="text-xs text-gray-400 mt-2">AI & Machine Learning</div>
                             </div>
                             
                             <!-- Stanford logo reference -->
                             <div class="absolute bottom-0 left-0 p-8 bg-white/5 rounded-lg border border-white/10">
                                 <div class="text-sm text-gray-500 mb-2">Alumni</div>
                                 <div class="text-2xl font-bold text-white">Stanford</div>
                             </div>
                             
                             <!-- X Moonshot reference -->
                             <div class="absolute bottom-0 right-0 p-8 bg-white/5 rounded-lg border border-white/10">
                                 <div class="text-sm text-gray-500 mb-2">Experience from</div>
                                 <div class="text-2xl font-bold text-white">X Factory</div>
                             </div>
                             
                             <!-- Center element -->
                             <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-24 h-24 rounded-full bg-primary-500/20 border-2 border-primary-500 flex items-center justify-center">
                                 <svg width="48" height="52" viewBox="0 0 97 105" fill="none" xmlns="http://www.w3.org/2000/svg">
                                     <path opacity="0.8" d="M0.84375 29.5892V75.3785L43.791 45.7896V0L0.84375 29.5892Z" fill="white"/>
                                     <path opacity="0.8" d="M0.84375 75.3787V29.5891L43.791 59.1783V104.968L0.84375 75.3787Z" fill="white"/>
                                     <path opacity="0.8" d="M96.8438 29.5891V75.3787L53.8965 45.7895V0L96.8438 29.5891Z" fill="white"/>
                                     <path opacity="0.8" d="M96.8438 75.3787V29.5891L53.8965 59.1783V104.968L96.8438 75.3787Z" fill="white"/>
                                 </svg>
                             </div>
                         </div>
                     </div>
                </div>
			</div>
		</div>
	</div>
</section>
