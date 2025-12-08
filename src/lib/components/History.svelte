<script>
    import { ArrowRight } from 'lucide-svelte';
</script>

<section class="py-12 bg-white">
    <div class="mx-auto max-w-7xl px-6">
        <div class="relative rounded-2xl overflow-hidden h-[600px]">
            <img src="https://images.unsplash.com/photo-1579684385127-1ef15d508118?ixlib=rb-4.0.3&auto=format&fit=crop&w=1600&q=80" alt="History" class="absolute inset-0 h-full w-full object-cover" />
            
            <div class="absolute bottom-12 left-12 bg-[#b0ccfc] p-10 rounded-xl max-w-md">
                <div class="text-sm font-medium text-gray-900 mb-2">About</div>
                <h3 class="font-display text-3xl text-gray-900 mb-4">
                    A long history in healthcare
                </h3>
                <p class="text-gray-800 mb-6 leading-relaxed">
                    Get to know the full story of how Fabric came to be and learn about the team that made it happen.
                </p>
                <a href="#" class="inline-flex items-center text-gray-900 font-medium hover:underline">
                    Learn about us <ArrowRight size={16} class="ml-2" />
                </a>
            </div>
        </div>
    </div>
</section>

<section class="py-20 bg-white">
    <div class="mx-auto max-w-7xl px-6 text-center">
        <h3 class="font-display text-2xl text-gray-900 mb-12">Backed by leading investors</h3>
        <div class="flex flex-wrap justify-center items-center gap-12 opacity-60 grayscale">
            <!-- Placeholder for investor logos -->
            <span class="text-xl font-bold">LUX</span>
            <span class="text-xl font-bold">Vast Ventures</span>
            <span class="text-xl font-bold">General Catalyst</span>
            <span class="text-xl font-bold">GV</span>
            <span class="text-xl font-bold">Salesforce Ventures</span>
            <span class="text-xl font-bold">Thrive Capital</span>
            <span class="text-xl font-bold">Atento Capital</span>
        </div>
    </div>
</section>
