<script lang="ts">
    import { Check } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white border-t border-white/5">
	<div class="max-w-[1400px] mx-auto px-6">
		<h2 class="text-4xl font-serif font-normal mb-16">Pricing</h2>

		<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
			<!-- Enterprise -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Enterprise</h3>
				<p class="text-gray-400 text-sm mb-6">Custom</p>
				<button class="bg-white text-black px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-gray-200 transition-colors">
					Book an intro
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">EVERYTHING IN TEAM +</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-[#a3e635] flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Unlimited members per workspace and documents per integration</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-[#a3e635] flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Enterprise integrations</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-[#a3e635] flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Domain verification, SAML-based SSO, and SCIM</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-[#a3e635] flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Extended range of LLMs</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-[#a3e635] flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Analytics dashboard to measure impact</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-[#a3e635] flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Dedicated success team, priority support, and SLA</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-[#a3e635] flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>API access for building your own integrations</span>
					</li>
				</ul>
			</div>

			<!-- Team -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Team</h3>
				<p class="text-orange-500 text-sm mb-6">$30 / user per month</p>
				<button class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors">
					Sign up
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">EVERYTHING IN FREE +</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-orange-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Unlimited queries and meeting recordings</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-orange-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Up to 50 members per workspace</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-orange-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Our most popular integrations incl. Asana, Gmail, Outlook email, Zendesk, and more.</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-orange-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>OpenAI and Claude model selection</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-orange-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Enterprise data processing agreement</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-orange-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>10,000 documents per integration</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-orange-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Priority in-email and chat support</span>
					</li>
				</ul>
			</div>

			<!-- Free -->
			<div>
				<h3 class="text-xl font-bold mb-2">Free</h3>
				<p class="text-pink-500 text-sm mb-6">$0</p>
				<button class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors">
					Try it free
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">IDEAL FOR INDIVIDUALS</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>10 meetings per month — invite members for more</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Up to 5 members per workspace</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Unlimited assistants and prompt templates</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Meeting integrations with Calendar, Drive, Meet, Teams, and Zoom</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Data integrations with Confluence, Google Drive, OneDrive, Notion, and Sharepoint</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>1000 documents per integration</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Help center support</span>
					</li>
				</ul>
			</div>
		</div>
	</div>
</section>
