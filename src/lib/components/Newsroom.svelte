<script>
    import { ArrowLeft, ArrowRight } from 'lucide-svelte';
    import Button from './Button.svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-6">
        <div class="flex items-center justify-between mb-12">
            <h2 class="font-display text-4xl text-gray-900">Newsroom</h2>
            <div class="flex items-center gap-4">
                <div class="flex gap-2">
                    <button class="h-10 w-10 rounded-full border border-gray-200 flex items-center justify-center hover:bg-gray-50">
                        <ArrowLeft size={18} />
                    </button>
                    <button class="h-10 w-10 rounded-full border border-gray-200 flex items-center justify-center hover:bg-gray-50">
                        <ArrowRight size={18} />
                    </button>
                </div>
                <a href="#" class="text-sm font-medium text-gray-600 hover:text-gray-900 flex items-center">
                    View all <ArrowRight size={16} class="ml-1" />
                </a>
            </div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- News Item 1 -->
            <div class="group cursor-pointer">
                <div class="flex items-center gap-3 mb-4">
                    <span class="bg-blue-100 text-blue-800 text-xs font-semibold px-2 py-1 rounded">News</span>
                    <span class="text-xs text-gray-500">Fierce Healthcare</span>
                </div>
                <h3 class="font-display text-xl text-gray-900 mb-4 group-hover:text-blue-600 transition-colors">
                    Fabric buys UCM Digital Health to expand reach to payers, employers
                </h3>
                <div class="text-xs text-gray-400">November 13, 2023</div>
                <div class="mt-4 flex items-center text-sm font-medium text-transparent group-hover:text-gray-900 transition-colors">
                    Read more <ArrowRight size={16} class="ml-2" />
                </div>
            </div>

             <!-- News Item 2 -->
             <div class="group cursor-pointer">
                <div class="flex items-center gap-3 mb-4">
                    <span class="bg-blue-100 text-blue-800 text-xs font-semibold px-2 py-1 rounded">News</span>
                    <span class="text-xs text-gray-500">Endpoints News</span>
                </div>
                <h3 class="font-display text-xl text-gray-900 mb-4 group-hover:text-blue-600 transition-colors">
                    Health IT startup Fabric buys UCM Digital Health — its fifth acquisition in three years
                </h3>
                <div class="text-xs text-gray-400">November 11, 2023</div>
                 <div class="mt-4 flex items-center text-sm font-medium text-transparent group-hover:text-gray-900 transition-colors">
                    Read more <ArrowRight size={16} class="ml-2" />
                </div>
            </div>

             <!-- News Item 3 -->
             <div class="group cursor-pointer">
                <div class="flex items-center gap-3 mb-4">
                    <span class="bg-blue-100 text-blue-800 text-xs font-semibold px-2 py-1 rounded">News</span>
                    <span class="text-xs text-gray-500">Health Tech World</span>
                </div>
                <h3 class="font-display text-xl text-gray-900 mb-4 group-hover:text-blue-600 transition-colors">
                    Fabric buys UCM Digital Health to expand reach to payers, employers
                </h3>
                <div class="text-xs text-gray-400">November 13, 2023</div>
                 <div class="mt-4 flex items-center text-sm font-medium text-transparent group-hover:text-gray-900 transition-colors">
                    Read more <ArrowRight size={16} class="ml-2" />
                </div>
            </div>
        </div>

        <div class="mt-24 border-t border-gray-100 pt-12">
            <div class="text-center text-xs text-gray-400 mb-8">A trusted, secure, and accessible platform.</div>
            <div class="flex justify-center gap-12 grayscale opacity-60">
                <!-- Compliance Logos -->
                <div class="flex items-center gap-2">
                    <div class="h-10 w-10 border-2 border-gray-400 rounded-full flex items-center justify-center font-bold text-[10px]">HIPAA</div>
                </div>
                 <div class="flex items-center gap-2">
                    <div class="h-10 w-10 border-2 border-gray-400 rounded-full flex items-center justify-center font-bold text-[10px]">SOC2</div>
                </div>
                 <div class="flex items-center gap-2">
                    <div class="h-10 w-10 border-2 border-gray-400 rounded-full flex items-center justify-center font-bold text-[10px]">WCAG</div>
                </div>
            </div>
        </div>

        <!-- Blue CTA Banner -->
        <div class="mt-24 bg-[#e0f2fe] rounded-2xl p-12 flex flex-col md:flex-row items-center justify-between">
            <div class="max-w-xl">
                <h2 class="font-display text-4xl text-gray-900 mb-4">See Fabric in action</h2>
                <p class="text-gray-600">
                    Fabric creates operational and clinical efficiency that expands access while providing consumer-grade care experiences that drive better outcomes and savings for health systems, employers, brokers, and health plans alike.
                </p>
            </div>
            <div class="mt-8 md:mt-0">
                <Button type="primary">Request a demo</Button>
            </div>
        </div>
    </div>
</section>
