<script>
    import { ArrowRight } from 'lucide-svelte';
</script>

<footer class="bg-[#f8f8f8] pt-24 pb-12 overflow-hidden relative">
    <div class="mx-auto max-w-7xl px-6 relative z-10">
        <div class="flex flex-col lg:flex-row justify-between gap-16 mb-24">
            <!-- Newsletter -->
            <div class="max-w-sm">
                <h3 class="font-display text-3xl text-gray-900 mb-4">Stay in the loop</h3>
                <p class="text-gray-500 text-sm mb-6">Keep up to date with all things Fabric by signing up for our newsletter.</p>
                <div class="relative">
                    <input type="email" placeholder="Get our newsletter" class="w-full rounded-full border border-gray-200 bg-white px-6 py-3 text-sm focus:outline-none focus:border-blue-300" />
                    <button class="absolute right-2 top-1/2 -translate-y-1/2 p-2 text-gray-400 hover:text-gray-600">
                        <ArrowRight size={16} />
                    </button>
                </div>
                <p class="text-[10px] text-gray-400 mt-4 leading-tight">
                    By submitting your email address, you agree to receive marketing emails from Fabric Health. You can unsubscribe at any time. View our Privacy Policy and Terms of Service.
                </p>
            </div>

            <!-- Links -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-8 text-sm">
                <div class="space-y-4">
                    <h4 class="font-bold text-gray-900">Platform & Services</h4>
                    <ul class="space-y-2 text-gray-600">
                        <li><a href="#" class="hover:text-gray-900">AI Assistant</a></li>
                        <li><a href="#" class="hover:text-gray-900">Engagement & Pathways</a></li>
                        <li><a href="#" class="hover:text-gray-900">Virtual Care Platform</a></li>
                        <li><a href="#" class="hover:text-gray-900">Virtual Care Service</a></li>
                        <li><a href="#" class="hover:text-gray-900">Intake & Care Guides</a></li>
                        <li><a href="#" class="hover:text-gray-900">Enterprise Features</a></li>
                    </ul>
                </div>
                <div class="space-y-4">
                    <h4 class="font-bold text-gray-900">Solutions</h4>
                    <ul class="space-y-2 text-gray-600">
                        <li><a href="#" class="hover:text-gray-900">For Health Systems</a></li>
                        <li><a href="#" class="hover:text-gray-900">For Health Plans</a></li>
                        <li><a href="#" class="hover:text-gray-900">For Employers</a></li>
                        <li><a href="#" class="hover:text-gray-900">For Brokers</a></li>
                        <li><a href="#" class="hover:text-gray-900">All Organization Types</a></li>
                    </ul>
                </div>
                <div class="space-y-4">
                    <h4 class="font-bold text-gray-900">Resources</h4>
                    <ul class="space-y-2 text-gray-600">
                        <li><a href="#" class="hover:text-gray-900">All Resources</a></li>
                        <li><a href="#" class="hover:text-gray-900">Blog</a></li>
                        <li><a href="#" class="hover:text-gray-900">Guides</a></li>
                        <li><a href="#" class="hover:text-gray-900">Case Studies</a></li>
                        <li><a href="#" class="hover:text-gray-900">Videos & Webinars</a></li>
                    </ul>
                </div>
                <div class="space-y-4">
                    <h4 class="font-bold text-gray-900">Company</h4>
                    <ul class="space-y-2 text-gray-600">
                        <li><a href="#" class="hover:text-gray-900">About</a></li>
                        <li><a href="#" class="hover:text-gray-900">Press</a></li>
                        <li><a href="#" class="hover:text-gray-900">Careers</a></li>
                        <li><a href="#" class="hover:text-gray-900">Contact</a></li>
                    </ul>
                </div>
                 <div class="space-y-4">
                    <h4 class="font-bold text-gray-900">Connect</h4>
                    <ul class="space-y-2 text-gray-600">
                        <li><a href="#" class="hover:text-gray-900">LinkedIn</a></li>
                        <li><a href="#" class="hover:text-gray-900">Facebook</a></li>
                        <li><a href="#" class="hover:text-gray-900">X (Twitter)</a></li>
                        <li><a href="#" class="hover:text-gray-900">Email Opt-In</a></li>
                    </ul>
                </div>
            </div>
        </div>
        
        <div class="flex flex-col md:flex-row justify-between items-end border-t border-gray-200 pt-8">
             <div class="text-xs text-gray-500">
                &copy; 2024 Fabric Labs, Inc. All rights reserved.
            </div>
             <div class="flex gap-6 text-xs text-gray-500 mt-4 md:mt-0">
                <a href="#" class="hover:text-gray-900">Privacy Policy</a>
                <a href="#" class="hover:text-gray-900">Terms & Conditions</a>
                <a href="#" class="hover:text-gray-900">Applicant & Candidate Privacy Notice</a>
            </div>
        </div>
    </div>

    <!-- Big Watermark -->
    <div class="absolute bottom-[-5%] left-1/2 -translate-x-1/2 pointer-events-none select-none opacity-[0.03]">
        <span class="font-display text-[400px] leading-none text-gray-900">fabric</span>
    </div>
</footer>
