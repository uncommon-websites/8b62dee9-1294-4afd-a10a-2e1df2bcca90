<script>
    let activeTab = 'Health Systems';
    const tabs = ['Health Systems', 'Health Plans', 'Employers'];

    const partners = [
        {
            name: 'SSM Health',
            logo: 'https://upload.wikimedia.org/wikipedia/commons/thumb/8/8d/SSM_Health_logo.svg/2560px-SSM_Health_logo.svg.png'
        },
        {
            name: 'Intermountain Health',
            logo: 'https://upload.wikimedia.org/wikipedia/commons/thumb/6/63/Intermountain_Healthcare_logo.svg/2560px-Intermountain_Healthcare_logo.svg.png'
        },
        {
            name: 'OSF HealthCare',
            logo: 'https://upload.wikimedia.org/wikipedia/commons/e/e8/OSF_HealthCare_Logo.png'
        },
        {
            name: 'MUSC Health',
            logo: 'https://muschealth.org/-/media/images/logos/musc-health-logo-black.png'
        }
    ];
</script>

<section class="py-12 bg-white border-b border-gray-100">
    <div class="mx-auto max-w-7xl px-6">
        <div class="flex flex-col md:flex-row items-center justify-between gap-8">
            <div class="flex items-center gap-8">
                <h2 class="font-display text-2xl text-gray-900">Partners</h2>
                
                <div class="flex gap-2">
                    {#each tabs as tab}
                        <button 
                            class="px-4 py-2 rounded-full text-sm font-medium transition-colors border {activeTab === tab ? 'bg-gray-900 text-white border-gray-900' : 'bg-white text-gray-600 border-gray-200 hover:border-gray-300'}"
                            on:click={() => activeTab = tab}
                        >
                            {tab}
                        </button>
                    {/each}
                </div>
            </div>

            <div class="flex items-center gap-12 grayscale opacity-60">
                {#each partners as partner}
                    <img src={partner.logo} alt={partner.name} class="h-8 w-auto object-contain" />
                {/each}
            </div>
        </div>
    </div>
</section>
