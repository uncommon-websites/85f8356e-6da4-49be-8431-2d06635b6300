<script lang="ts">
    // Simple SVG paths for icons would be better, but for now using colored squares/circles to mimic brand colors
    const integrations = [
        { name: 'Google Drive', color: 'bg-green-500' },
        { name: 'Teams', color: 'bg-indigo-500' },
        { name: 'Slack', color: 'bg-purple-500' },
        { name: 'Salesforce', color: 'bg-blue-400' },
        { name: 'HubSpot', color: 'bg-orange-500' },
        { name: 'ServiceNow', color: 'bg-green-700' },
        { name: 'SharePoint', color: 'bg-teal-600' },
        { name: 'OneDrive', color: 'bg-blue-600' },
        { name: 'Outlook', color: 'bg-blue-500' },
        { name: 'Workday', color: 'bg-blue-700' },
        { name: 'Figma', color: 'bg-purple-400' },
        { name: 'GitHub', color: 'bg-white' },
        { name: 'Zendesk', color: 'bg-green-400' },
        { name: 'Gmail', color: 'bg-red-500' },
        { name: 'Confluence', color: 'bg-blue-300' },
        { name: 'Jira', color: 'bg-blue-500' }
    ];

    const security = [
        'Custom user roles', 'SCIM provisioning', 'Advanced permissions', 'Private LLMs', 
        'SOC 2 Type 2', 'GDPR compliant', 'ISO 27001', 'Encryption', 
        'SAML single sign-on', 'Domain verification', 'Regional deploys', 'Audit logging'
    ];
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6 text-center">
		<h2 class="text-4xl md:text-5xl lg:text-6xl font-serif font-normal mb-6">
			Enterprise-grade<br />
			integrations and security
		</h2>
		<p class="text-gray-400 text-lg max-w-2xl mx-auto mb-20">
			Sana connects with 100+ applications and unifies your company's data securely.
		</p>

		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20">
            <!-- Integrations -->
			<div>
                <div class="inline-block bg-[#3b82f6] text-white text-[10px] font-bold px-3 py-1 rounded-full mb-8 tracking-wide uppercase">
                    Connect your daily tools seamlessly
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
                <div class="inline-block bg-[#3b82f6] text-white text-[10px] font-bold px-3 py-1 rounded-full mb-8 tracking-wide uppercase">
                    Security you can stand by
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
