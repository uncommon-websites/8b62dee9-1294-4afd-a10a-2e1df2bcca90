<script>
    import { ArrowRight } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-6">
        <div class="mb-12">
            <div class="text-sm font-medium text-gray-500 mb-2">Case Studies</div>
            <h2 class="font-display text-4xl md:text-5xl text-gray-900 leading-tight max-w-3xl">
                Create operational and clinical efficiency while expanding access
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-6 h-auto md:h-[600px]">
            <!-- Large Dark Card -->
            <div class="md:col-span-2 bg-[#0f172a] rounded-2xl p-10 flex flex-col justify-between relative overflow-hidden group">
                <div class="relative z-10">
                    <div class="text-white font-bold text-xl mb-12 flex items-center gap-2">
                        <div class="h-6 w-6 bg-blue-500 rounded-full"></div> Luminis Health.
                    </div>
                    <h3 class="font-display text-4xl md:text-5xl text-white mb-8">
                        How Fabric fit Luminis Health
                    </h3>
                    <blockquote class="text-gray-300 text-lg leading-relaxed mb-8 max-w-xl">
                        "As one of the busiest Emergency Departments in the country, our staff immediately noticed the difference. Nurses are saving time and seeing patients faster, and patients appreciate the streamlined intake process and the digital transparency provided from the very beginning."
                    </blockquote>
                    <div class="text-white">
                        <div class="font-bold">Saad Chaudhry</div>
                        <div class="text-sm text-gray-400">Chief Digital & Information Officer at Luminis Health</div>
                    </div>
                </div>
                <div class="mt-8 relative z-10">
                    <a href="#" class="inline-flex items-center text-white font-medium hover:underline">
                        Get the case study <ArrowRight size={16} class="ml-2" />
                    </a>
                </div>
            </div>

            <!-- Right Column Cards -->
            <div class="flex flex-col gap-6">
                <!-- Top Card (Salmon) -->
                <div class="flex-1 bg-[#ffddd6] rounded-2xl p-8 flex flex-col justify-between group hover:bg-[#ffcec5] transition-colors">
                    <div class="text-gray-900 font-bold mb-4">OSF</div>
                    <h3 class="font-display text-2xl text-gray-900 mb-4">
                        How Fabric saved OSF $2.4 million in one year with conversational AI
                    </h3>
                    <a href="#" class="inline-flex items-center text-gray-900 font-medium text-sm hover:underline mt-auto">
                        Get the case study <ArrowRight size={16} class="ml-2" />
                    </a>
                </div>

                <!-- Bottom Card (Green) -->
                <div class="flex-1 bg-[#5f8b76] rounded-2xl p-8 flex flex-col justify-between group hover:bg-[#537a68] transition-colors">
                     <div class="text-white font-bold mb-4">Intermountain Health</div>
                    <h3 class="font-display text-2xl text-white mb-4">
                        How Fabric leveraged AI to reduce call center volume by 30% for Intermountain Healthcare
                    </h3>
                    <a href="#" class="inline-flex items-center text-white font-medium text-sm hover:underline mt-auto">
                        Get the case study <ArrowRight size={16} class="ml-2" />
                    </a>
                </div>
            </div>
        </div>
    </div>
</section>
