<script>
    const partners = [
        { name: 'FYZICAL Therapy & Balance Centers' },
        { name: 'Spooner Physical Therapy' },
        { name: 'Mountain Land Physical Therapy' },
        { name: 'Therapeutic Associates' },
        { name: 'Highbar Physical Therapy' },
        { name: 'Atlantic Physical Therapy Center' }
    ];
</script>

<section class="py-16 bg-gray-50 border-y border-gray-100">
    <div class="mx-auto max-w-7xl px-6">
        <div class="text-center mb-12">
            <h2 class="font-display text-sm font-semibold text-gray-500 uppercase tracking-wide mb-6">Trusted by Leading PT Practices</h2>
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-8 items-center">
                {#each partners as partner}
                    <div class="flex items-center justify-center">
                        <span class="text-sm font-medium text-gray-400 text-center">{partner.name}</span>
                    </div>
                {/each}
            </div>
        </div>
        <div class="text-center">
            <p class="text-gray-600 text-sm">Join 500+ physical therapy practices growing with Second Door</p>
        </div>
    </div>
</section>
