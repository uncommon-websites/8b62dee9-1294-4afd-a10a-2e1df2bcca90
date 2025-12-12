<script lang="ts">
    let activeIndex = 0;
    const items = [
        { title: "Automate Marketing & Lead Generation", content: "Maximize patient volume with automated campaigns, smart booking rules, and digital front door tools that convert website visitors into patients." },
        { title: "Secure Employer Contracts", content: "Access employer discovery tools, prospecting automation, and D2E contracting expertise to tap into the $50B MSK market." },
        { title: "Optimize Revenue & Case Mix", content: "Increase patient lifetime value with cash pay programs, manage volume intelligently, and control your payer mix for sustainable growth." }
    ];
</script>

<section class="py-24 bg-gray-50 relative overflow-hidden">
    <!-- Background Gradient -->
    <div class="absolute inset-0 bg-gradient-to-br from-primary-50/30 to-transparent pointer-events-none"></div>

    <div class="max-w-[1440px] mx-auto px-6 relative z-10 grid lg:grid-cols-2 gap-20 items-center">
        <!-- Left Content -->
        <div>
            <h2 class="text-4xl md:text-5xl font-heading leading-tight mb-12">
                From schedule-full to margin-strong: Your growth path to direct employer contracts
            </h2>

            <!-- Growth Path Visual -->
            <div class="relative w-full aspect-square max-w-md mx-auto lg:mx-0">
                <!-- Concentric Circles -->
                <div class="absolute inset-0 flex items-center justify-center">
                    <div class="w-[100%] h-[100%] border border-primary-200/50 rounded-full absolute"></div>
                    <div class="w-[80%] h-[80%] border border-primary-200/50 rounded-full absolute"></div>
                    <div class="w-[60%] h-[60%] border border-primary-200/50 rounded-full absolute"></div>
                    <div class="w-[40%] h-[40%] border border-primary-200/50 rounded-full absolute"></div>
                    <div class="w-[20%] h-[20%] bg-primary-100 rounded-full absolute shadow-[0_0_40px_rgba(99,179,164,0.2)]"></div>
                </div>

                <!-- Cards on Radar -->
                <div class="absolute top-[20%] right-[10%] bg-white/80 backdrop-blur shadow-sm p-3 rounded-lg border border-white text-xs flex items-center gap-2">
                    <div class="w-2 h-2 bg-primary-500 rounded-full"></div>
                    Marketing Automation
                </div>

                <div class="absolute bottom-[35%] left-[10%] bg-white shadow-lg p-4 rounded-xl border border-gray-100 max-w-[200px]">
                    <div class="flex items-start gap-3">
                        <div class="w-4 h-4 bg-primary-500 rounded-full mt-0.5 shrink-0"></div>
                        <div>
                            <p class="text-xs font-medium text-gray-900">Employer contracts secured</p>
                        </div>
                    </div>
                </div>

                <div class="absolute top-[50%] right-[5%] bg-white shadow-lg p-3 rounded-lg border border-gray-100 text-xs">
                    <div class="font-semibold text-gray-900 mb-1">Revenue Growth</div>
                    <div class="text-primary-600 font-bold">+34%</div>
                </div>
            </div>
        </div>

        <!-- Right Content (Accordion) -->
        <div class="space-y-4">
            {#each items as item, i}
                <div class="border-b border-gray-200 pb-4">
                    <button 
                        class="w-full flex justify-between items-center py-4 text-left group"
                        on:click={() => activeIndex = i}
                    >
                        <span class="text-xl font-medium {activeIndex === i ? 'text-gray-900' : 'text-gray-600'}">
                            {item.title}
                        </span>
                        <span class="text-2xl font-light text-gray-400 group-hover:text-gray-900">
                            {activeIndex === i ? '−' : '+'}
                        </span>
                    </button>
                    
                    {#if activeIndex === i}
                        <div class="pb-4 text-gray-600">
                            <p class="mb-4">{item.content}</p>
                            <a href="#" class="text-sm font-medium text-gray-900 hover:underline inline-flex items-center gap-1">
                                Learn more 
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-3 h-3"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5 21 12m0 0-7.5 7.5M21 12H3" /></svg>
                            </a>
                        </div>
                    {/if}
                </div>
            {/each}
        </div>
    </div>
</section>
