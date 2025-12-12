<script>
    import { ArrowRight } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-6">
        <div class="mb-12">
            <div class="text-sm font-medium text-gray-500 mb-2">Customer Success Stories</div>
            <h2 class="font-display text-4xl md:text-5xl text-gray-900 leading-tight max-w-3xl">
                Real results from PT practices using Second Door
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-6 h-auto md:h-[600px]">
            <!-- Large Dark Card -->
            <div class="md:col-span-2 bg-gray-900 rounded-2xl p-10 flex flex-col justify-between relative overflow-hidden group">
                <div class="relative z-10">
                    <div class="text-white font-bold text-xl mb-12 flex items-center gap-2">
                        <div class="h-6 w-6 bg-primary-500 rounded-full"></div> Atlantic Physical Therapy Center
                    </div>
                    <h3 class="font-display text-4xl md:text-5xl text-white mb-8">
                        Complete practice transformation
                    </h3>
                    <blockquote class="text-gray-300 text-lg leading-relaxed mb-8 max-w-xl">
                        "Second Door Health has completely transformed how we run our practice. From streamlining our scheduling and lead management to helping us secure employer contracts, it's been a game-changer. The platform is intuitive, and the support team is incredible. We've seen measurable growth in revenue and patient satisfaction."
                    </blockquote>
                    <div class="text-white">
                        <div class="font-bold">Dave Manzo</div>
                        <div class="text-sm text-gray-400">CFO, Atlantic Physical Therapy Center</div>
                    </div>
                </div>
                <div class="mt-8 relative z-10">
                    <a href="#" class="inline-flex items-center text-white font-medium hover:underline">
                        Read the full story <ArrowRight size={16} class="ml-2" />
                    </a>
                </div>
            </div>

            <!-- Right Column Cards -->
            <div class="flex flex-col gap-6">
                <!-- Top Card (Teal) -->
                <div class="flex-1 bg-primary-100 rounded-2xl p-8 flex flex-col justify-between group hover:bg-primary-200 transition-colors">
                    <div class="text-gray-900 font-bold mb-4">Pittman Physical Therapy</div>
                    <h3 class="font-display text-2xl text-gray-900 mb-4">
                        Jumpstarting D2E efforts with immediate value
                    </h3>
                    <a href="#" class="inline-flex items-center text-gray-900 font-medium text-sm hover:underline mt-auto">
                        Read their story <ArrowRight size={16} class="ml-2" />
                    </a>
                </div>

                <!-- Bottom Card (Dark Teal) -->
                <div class="flex-1 bg-primary-700 rounded-2xl p-8 flex flex-col justify-between group hover:bg-primary-800 transition-colors">
                     <div class="text-white font-bold mb-4">FYZICAL Therapy & Balance Centers</div>
                    <h3 class="font-display text-2xl text-white mb-4">
                        Scaling direct employer contracts across multiple locations
                    </h3>
                    <a href="#" class="inline-flex items-center text-white font-medium text-sm hover:underline mt-auto">
                        Read their story <ArrowRight size={16} class="ml-2" />
                    </a>
                </div>
            </div>
        </div>
    </div>
</section>
