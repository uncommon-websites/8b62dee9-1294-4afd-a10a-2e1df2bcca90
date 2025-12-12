<script lang="ts">
    const cards = [
        {
            title: "Employer Discovery & Contracting",
            image: "https://images.unsplash.com/photo-1556761175-b413da4baf72?q=80&w=2000&auto=format&fit=crop",
            alt: "Business meeting"
        },
        {
            title: "Marketing Automation",
            image: "https://images.unsplash.com/photo-1460925895917-afdab827c52f?q=80&w=2000&auto=format&fit=crop",
            alt: "Marketing dashboard"
        },
        {
            title: "EMR Integration & Outcomes",
            image: "https://images.unsplash.com/photo-1576091160399-112ba8d25d1d?q=80&w=2000&auto=format&fit=crop",
            alt: "Healthcare technology"
        }
    ];
</script>

<section class="py-24 bg-white">
    <div class="max-w-[1440px] mx-auto px-6">
        <div class="flex flex-col md:flex-row justify-between items-end mb-12">
            <div class="max-w-2xl">
                <h2 class="text-4xl md:text-5xl font-heading mb-6">
                    Everything you need to grow your direct-pay PT practice
                </h2>
                <p class="text-gray-600 max-w-xl">
                    Second Door provides the complete platform for physical therapy practices to automate marketing, secure employer contracts, and scale to direct-pay models—all while working alongside your existing workflows.
                </p>
            </div>
            
            <div class="flex gap-4 mt-8 md:mt-0">
                <button class="w-12 h-12 rounded-full border border-gray-200 flex items-center justify-center hover:bg-gray-50 transition-colors">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5"><path stroke-linecap="round" stroke-linejoin="round" d="M10.5 19.5 3 12m0 0 7.5-7.5M3 12h18" /></svg>
                </button>
                <button class="w-12 h-12 rounded-full border border-gray-200 flex items-center justify-center hover:bg-gray-50 transition-colors">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5 21 12m0 0-7.5 7.5M21 12H3" /></svg>
                </button>
            </div>
        </div>

        <div class="grid md:grid-cols-3 gap-6">
            {#each cards as card}
                <div class="group cursor-pointer">
                    <div class="aspect-[4/3] overflow-hidden rounded-sm mb-0">
                        <img src={card.image} alt={card.alt} class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" />
                    </div>
                    <div class="bg-gray-900 text-white p-4">
                        <h3 class="text-lg font-medium">{card.title}</h3>
                    </div>
                </div>
            {/each}
        </div>
        
        <div class="mt-16 grid md:grid-cols-3 gap-8">
            <div class="text-center">
                <div class="text-4xl font-bold text-gray-900 mb-2">$99</div>
                <div class="text-sm text-gray-600">Starting price per location/month</div>
            </div>
            <div class="text-center">
                <div class="text-4xl font-bold text-gray-900 mb-2">30 Days</div>
                <div class="text-sm text-gray-600">Average time to go live</div>
            </div>
            <div class="text-center">
                <div class="text-4xl font-bold text-gray-900 mb-2">500+</div>
                <div class="text-sm text-gray-600">PT practices in our network</div>
            </div>
        </div>
    </div>
</section>
