<script>
    import { ArrowRight } from 'lucide-svelte';
</script>

<footer class="bg-[#f8f8f8] pt-24 pb-12 overflow-hidden relative">
    <div class="mx-auto max-w-7xl px-6 relative z-10">
        <div class="flex flex-col lg:flex-row justify-between gap-16 mb-24">
            <!-- Newsletter -->
            <div class="max-w-sm">
                <h3 class="font-display text-3xl text-gray-900 mb-4">Stay in the loop</h3>
                <p class="text-gray-500 text-sm mb-6">Get the latest insights on PT practice growth, employer contracting, and direct-pay strategies.</p>
                <div class="relative">
                    <input type="email" placeholder="Enter your email" class="w-full rounded-full border border-gray-200 bg-white px-6 py-3 text-sm focus:outline-none focus:border-primary-300" />
                    <button class="absolute right-2 top-1/2 -translate-y-1/2 p-2 text-gray-400 hover:text-gray-600">
                        <ArrowRight size={16} />
                    </button>
                </div>
                <p class="text-[10px] text-gray-400 mt-4 leading-tight">
                    By submitting your email address, you agree to receive marketing emails from Second Door. You can unsubscribe at any time. View our Privacy Policy and Terms of Service.
                </p>
            </div>

            <!-- Links -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-8 text-sm">
                <div class="space-y-4">
                    <h4 class="font-bold text-gray-900">Platform</h4>
                    <ul class="space-y-2 text-gray-600">
                        <li><a href="#" class="hover:text-gray-900">Employer Discovery</a></li>
                        <li><a href="#" class="hover:text-gray-900">Marketing Automation</a></li>
                        <li><a href="#" class="hover:text-gray-900">EMR Integration</a></li>
                        <li><a href="#" class="hover:text-gray-900">Outcomes Tracking</a></li>
                        <li><a href="#" class="hover:text-gray-900">Network Access</a></li>
                        <li><a href="#" class="hover:text-gray-900">Video Visits</a></li>
                    </ul>
                </div>
                <div class="space-y-4">
                    <h4 class="font-bold text-gray-900">Solutions</h4>
                    <ul class="space-y-2 text-gray-600">
                        <li><a href="#" class="hover:text-gray-900">Employer Contracting</a></li>
                        <li><a href="#" class="hover:text-gray-900">Cash Pay Programs</a></li>
                        <li><a href="#" class="hover:text-gray-900">Lead Generation</a></li>
                        <li><a href="#" class="hover:text-gray-900">Practice Growth</a></li>
                        <li><a href="#" class="hover:text-gray-900">Revenue Optimization</a></li>
                    </ul>
                </div>
                <div class="space-y-4">
                    <h4 class="font-bold text-gray-900">Resources</h4>
                    <ul class="space-y-2 text-gray-600">
                        <li><a href="#" class="hover:text-gray-900">Blog</a></li>
                        <li><a href="#" class="hover:text-gray-900">Guides & Downloads</a></li>
                        <li><a href="#" class="hover:text-gray-900">Case Studies</a></li>
                        <li><a href="#" class="hover:text-gray-900">Webinars</a></li>
                        <li><a href="#" class="hover:text-gray-900">Help Center</a></li>
                    </ul>
                </div>
                <div class="space-y-4">
                    <h4 class="font-bold text-gray-900">Company</h4>
                    <ul class="space-y-2 text-gray-600">
                        <li><a href="#" class="hover:text-gray-900">About Us</a></li>
                        <li><a href="#" class="hover:text-gray-900">Careers</a></li>
                        <li><a href="#" class="hover:text-gray-900">Contact</a></li>
                        <li><a href="#" class="hover:text-gray-900">Partners</a></li>
                    </ul>
                </div>
                 <div class="space-y-4">
                    <h4 class="font-bold text-gray-900">Connect</h4>
                    <ul class="space-y-2 text-gray-600">
                        <li><a href="#" class="hover:text-gray-900">LinkedIn</a></li>
                        <li><a href="#" class="hover:text-gray-900">Facebook</a></li>
                        <li><a href="#" class="hover:text-gray-900">Twitter</a></li>
                        <li><a href="#" class="hover:text-gray-900">YouTube</a></li>
                    </ul>
                </div>
            </div>
        </div>
        
        <div class="flex flex-col md:flex-row justify-between items-end border-t border-gray-200 pt-8">
             <div class="text-xs text-gray-500">
                &copy; 2024 Second Door. All rights reserved. Based in Phoenix, AZ.
            </div>
             <div class="flex gap-6 text-xs text-gray-500 mt-4 md:mt-0">
                <a href="#" class="hover:text-gray-900">Privacy Policy</a>
                <a href="#" class="hover:text-gray-900">Terms of Service</a>
                <a href="#" class="hover:text-gray-900">HIPAA Compliance</a>
            </div>
        </div>
    </div>

    <!-- Big Watermark -->
    <div class="absolute bottom-[-5%] left-1/2 -translate-x-1/2 pointer-events-none select-none opacity-[0.02]">
        <span class="font-display text-[300px] leading-none text-gray-900">Second Door</span>
    </div>
</footer>
