<script>
    import { ArrowRight } from 'lucide-svelte';
</script>

<section class="py-12 bg-white">
    <div class="mx-auto max-w-7xl px-6">
        <div class="relative rounded-2xl overflow-hidden h-[600px]">
            <img src="https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?ixlib=rb-4.0.3&auto=format&fit=crop&w=1600&q=80" alt="Phoenix skyline" class="absolute inset-0 h-full w-full object-cover" />
            
            <div class="absolute bottom-12 left-12 bg-primary-100 p-10 rounded-xl max-w-md">
                <div class="text-sm font-medium text-gray-900 mb-2">About Second Door</div>
                <h3 class="font-display text-3xl text-gray-900 mb-4">
                    Built by PT experts for PT practices
                </h3>
                <p class="text-gray-800 mb-6 leading-relaxed">
                    Based in Phoenix, AZ with remote work options. We're passionate about helping physical therapy practices thrive in the direct-pay model. Join our team or learn more about our mission.
                </p>
                <a href="#" class="inline-flex items-center text-gray-900 font-medium hover:underline">
                    Learn about our team <ArrowRight size={16} class="ml-2" />
                </a>
            </div>
        </div>
    </div>
</section>

<section class="py-20 bg-white">
    <div class="mx-auto max-w-7xl px-6">
        <div class="grid md:grid-cols-3 gap-12 text-center">
            <div>
                <div class="text-4xl font-bold text-gray-900 mb-2">$50B</div>
                <div class="text-gray-600">MSK market opportunity</div>
            </div>
            <div>
                <div class="text-4xl font-bold text-gray-900 mb-2">500+</div>
                <div class="text-gray-600">PT practices in our network</div>
            </div>
            <div>
                <div class="text-4xl font-bold text-gray-900 mb-2">30 Days</div>
                <div class="text-gray-600">Average implementation time</div>
            </div>
        </div>
    </div>
</section>
