<script lang="ts">
    let activeIndex = 0;
    const items = [
        { title: "Intelligent Access and Answers", content: "Offer consumer-grade care experiences and provide the right answers and care options." },
        { title: "Streamlined Care Experiences", content: "Seamlessly transition patients between virtual and in-person care settings." },
        { title: "Operational & Clinical Efficiency", content: "Automate administrative tasks and improve provider productivity." }
    ];
</script>

<section class="py-24 bg-blue-50/50 relative overflow-hidden">
    <!-- Background Gradient -->
    <div class="absolute inset-0 bg-gradient-to-br from-blue-100/50 to-transparent pointer-events-none"></div>

    <div class="max-w-[1440px] mx-auto px-6 relative z-10 grid lg:grid-cols-2 gap-20 items-center">
        <!-- Left Content -->
        <div>
            <h2 class="text-4xl md:text-5xl font-heading leading-tight mb-12">
                We drive better outcomes and savings for health systems, health plans, and employers
            </h2>

            <!-- Radar Visual -->
            <div class="relative w-full aspect-square max-w-md mx-auto lg:mx-0">
                <!-- Concentric Circles -->
                <div class="absolute inset-0 flex items-center justify-center">
                    <div class="w-[100%] h-[100%] border border-blue-200/50 rounded-full absolute"></div>
                    <div class="w-[80%] h-[80%] border border-blue-200/50 rounded-full absolute"></div>
                    <div class="w-[60%] h-[60%] border border-blue-200/50 rounded-full absolute"></div>
                    <div class="w-[40%] h-[40%] border border-blue-200/50 rounded-full absolute"></div>
                    <div class="w-[20%] h-[20%] bg-blue-100 rounded-full absolute shadow-[0_0_40px_rgba(59,130,246,0.2)]"></div>
                </div>

                <!-- Cards on Radar -->
                <div class="absolute top-[20%] right-[10%] bg-white/80 backdrop-blur shadow-sm p-3 rounded-lg border border-white text-xs flex items-center gap-2 animate-pulse">
                    <div class="w-2 h-2 bg-green-500 rounded-full"></div>
                    Patient seen virtually
                </div>

                <div class="absolute bottom-[35%] left-[10%] bg-white shadow-lg p-4 rounded-xl border border-gray-100 max-w-[200px]">
                    <div class="flex items-start gap-3">
                        <div class="w-4 h-4 bg-blue-500 rounded-full mt-0.5 shrink-0"></div>
                        <div>
                            <p class="text-xs font-medium text-gray-900">Patient referred for in-person care</p>
                        </div>
                    </div>
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
