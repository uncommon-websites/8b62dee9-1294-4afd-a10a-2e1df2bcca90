<script lang="ts">
    const cards = [
        {
            title: "AI Assistant",
            image: "https://images.unsplash.com/photo-1516575334481-f85287c2c81d?q=80&w=2000&auto=format&fit=crop",
            alt: "Person using phone on couch"
        },
        {
            title: "Provider Directory",
            image: "https://images.unsplash.com/photo-1559839734-2b71ea197ec2?q=80&w=2000&auto=format&fit=crop",
            alt: "Doctor looking at tablet"
        },
        {
            title: "Engagement & Pathways",
            image: "https://images.unsplash.com/photo-1522202176988-66273c2fd55f?q=80&w=2000&auto=format&fit=crop",
            alt: "Woman using phone"
        }
    ];
</script>

<section class="py-24">
    <div class="max-w-[1440px] mx-auto px-6">
        <div class="flex flex-col md:flex-row justify-between items-end mb-12">
            <div class="max-w-2xl">
                <h2 class="text-4xl md:text-5xl font-heading mb-6">
                    Meet our end-to-end care access platform and virtual care services
                </h2>
                <p class="text-gray-600 max-w-xl">
                    Fabric creates operational and clinical efficiency that expands access while providing consumer-grade care experiences that drive better outcomes and savings for health systems, employers, brokers, and health plans alike.
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
                    <div class="bg-[#1a2c38] text-white p-4">
                        <h3 class="text-lg font-medium">{card.title}</h3>
                    </div>
                </div>
            {/each}
        </div>
    </div>
</section>
