<script lang="ts">
    // Retail-focused integrations
    const integrations = [
        { name: 'SAP', color: 'bg-blue-500' },
        { name: 'Oracle Retail', color: 'bg-red-600' },
        { name: 'Shopify', color: 'bg-green-600' },
        { name: 'Salesforce', color: 'bg-blue-400' },
        { name: 'NetSuite', color: 'bg-orange-500' },
        { name: 'Microsoft Dynamics', color: 'bg-blue-600' },
        { name: 'Square', color: 'bg-black' },
        { name: 'BigCommerce', color: 'bg-blue-700' },
        { name: 'Magento', color: 'bg-orange-600' },
        { name: 'WooCommerce', color: 'bg-purple-600' },
        { name: 'Lightspeed', color: 'bg-orange-400' },
        { name: 'Vend', color: 'bg-teal-500' },
        { name: 'Clover', color: 'bg-green-500' },
        { name: 'Toast', color: 'bg-red-500' },
        { name: 'Manhattan', color: 'bg-indigo-600' },
        { name: 'Blue Yonder', color: 'bg-blue-800' }
    ];

    const security = [
        'Enterprise-grade security', 'Data encryption', 'SOC 2 compliant', 'GDPR compliant', 
        'Private cloud options', 'Custom data policies', 'Access controls', 'Audit trails', 
        'SAML SSO', 'API security', 'Regular audits', 'Compliance reporting'
    ];
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6 text-center">
		<h2 class="text-4xl md:text-5xl lg:text-6xl font-normal mb-6">
			Seamless integration<br />
			with your retail tech stack
		</h2>
		<p class="text-gray-600 text-lg max-w-2xl mx-auto mb-20">
			Connect with your existing systems—ERP, POS, e-commerce, and more—with enterprise-grade security.
		</p>

		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20">
            <!-- Integrations -->
			<div>
                <div class="inline-block bg-primary-500 text-black text-[10px] font-bold px-3 py-1 rounded-full mb-8 tracking-wide uppercase">
                    Retail System Integrations
                </div>
                
                <div class="grid grid-cols-4 gap-4">
                    {#each integrations as tool}
                        <div class="aspect-square bg-[#111] rounded-xl border border-white/5 flex flex-col items-center justify-center p-2 hover:bg-[#1a1a1a] transition-colors group">
                            <div class="w-8 h-8 rounded-lg {tool.color} mb-3 flex items-center justify-center opacity-80 group-hover:opacity-100 transition-opacity">
                                <!-- Simple icon placeholder -->
                            </div> 
                            <span class="text-[10px] text-gray-400 font-medium">{tool.name}</span>
                        </div>
                    {/each}
                </div>
            </div>

            <!-- Security -->
			<div>
                <div class="inline-block bg-primary-500 text-black text-[10px] font-bold px-3 py-1 rounded-full mb-8 tracking-wide uppercase">
                    Enterprise Security
                </div>
                
                <div class="grid grid-cols-4 gap-4">
                     {#each security as item}
                        <div class="aspect-square bg-[#111] rounded-xl border border-white/5 flex flex-col items-center justify-center p-2 hover:bg-[#1a1a1a] transition-colors group">
                            <div class="w-8 h-8 rounded-full border border-white/20 mb-3 flex items-center justify-center text-white/50 group-hover:text-white transition-colors">
                                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                    <path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/>
                                </svg>
                            </div> 
                            <span class="text-[10px] text-gray-400 text-center leading-tight font-medium">{item}</span>
                        </div>
                    {/each}
                </div>
            </div>
		</div>
	</div>
</section>
