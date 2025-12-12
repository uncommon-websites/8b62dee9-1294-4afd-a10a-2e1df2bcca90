<script lang="ts">
    const Check = `<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-gray-400"><path fill-rule="evenodd" d="M19.916 4.626a.75.75 0 0 1 .208 1.04l-9 13.5a.75.75 0 0 1-1.154.114l-6-6a.75.75 0 0 1 1.06-1.06l5.353 5.353 8.493-12.74a.75.75 0 0 1 1.04-.207Z" clip-rule="evenodd" /></svg>`;
</script>

<section class="py-24">
    <div class="max-w-[1440px] mx-auto px-6">
        <h2 class="text-4xl md:text-5xl font-heading mb-20 max-w-3xl">
            Built for PT practice owners who want to control their growth trajectory
        </h2>

        <!-- Section 1: Practice Owners -->
        <div class="grid lg:grid-cols-2 gap-16 mb-32 items-center">
            <div>
                <h3 class="text-2xl font-heading mb-8">For practice owners...</h3>
                <ul class="space-y-8 mb-10">
                    <li class="flex gap-4">
                        <div class="mt-1">{@html Check}</div>
                        <div>
                            <h4 class="font-medium text-gray-900">Automate Marketing</h4>
                            <p class="text-sm text-gray-600 mt-1">Maximize patient volume with digital front door tools, automated campaigns, and lead generation that converts.</p>
                        </div>
                    </li>
                    <li class="flex gap-4">
                        <div class="mt-1">{@html Check}</div>
                        <div>
                            <h4 class="font-medium text-gray-900">Secure Employer Contracts</h4>
                            <p class="text-sm text-gray-600 mt-1">Access employer discovery tools and D2E contracting expertise to establish fair payment agreements.</p>
                        </div>
                    </li>
                    <li class="flex gap-4">
                        <div class="mt-1">{@html Check}</div>
                        <div>
                            <h4 class="font-medium text-gray-900">Optimize Revenue</h4>
                            <p class="text-sm text-gray-600 mt-1">Control your payer mix, increase patient lifetime value, and reduce administrative costs.</p>
                        </div>
                    </li>
                </ul>
                <a href="#" class="inline-block px-6 py-2.5 rounded-full border border-gray-300 text-sm font-medium hover:bg-gray-50 transition-colors">
                    Get Started
                </a>
            </div>
            
            <div class="relative">
                <img src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?q=80&w=2000&auto=format&fit=crop" alt="Practice owner smiling" class="rounded-lg shadow-xl w-full max-w-md ml-auto object-cover h-[500px]" />
                
                <!-- Floating UI Card -->
                <div class="absolute top-10 left-0 bg-white rounded-lg shadow-2xl p-4 max-w-xs w-full text-xs border border-gray-100">
                    <div class="mb-3 pb-3 border-b">
                        <p class="text-gray-500 mb-1">Monthly Performance Dashboard</p>
                    </div>
                    <div class="mb-3">
                        <p class="font-medium mb-2">Revenue Growth</p>
                        <div class="flex items-center gap-2 mb-2">
                            <div class="text-2xl font-bold text-primary-600">+34%</div>
                            <span class="text-gray-500">vs last quarter</span>
                        </div>
                        <div class="flex gap-1 h-12 items-end">
                            <div class="w-1/4 bg-primary-200 rounded-t h-1/2"></div>
                            <div class="w-1/4 bg-primary-300 rounded-t h-3/4"></div>
                            <div class="w-1/4 bg-primary-400 rounded-t h-4/5"></div>
                            <div class="w-1/4 bg-primary-500 rounded-t h-full"></div>
                        </div>
                    </div>
                    <div>
                        <p class="font-medium mb-2">Employer Contracts</p>
                        <div class="bg-primary-50 p-2 rounded mb-2">
                            <p class="text-[10px] text-gray-700 font-medium">3 Active Contracts</p>
                            <p class="text-[10px] text-gray-500 mt-1">5 leads in pipeline</p>
                        </div>
                        <button class="w-full bg-gray-900 text-white py-1.5 rounded text-[10px]">View Employer Dashboard</button>
                    </div>
                </div>
            </div>
        </div>

        <!-- Section 2: Patients -->
        <div class="grid lg:grid-cols-2 gap-16 items-center">
            <div class="order-2 lg:order-1 relative">
                <img src="https://images.unsplash.com/photo-1576091160550-2173dba999ef?q=80&w=2000&auto=format&fit=crop" alt="Patient in physical therapy" class="rounded-lg shadow-xl w-full max-w-md object-cover h-[500px]" />
                
                <!-- Floating UI Card -->
                <div class="absolute bottom-20 right-0 bg-white rounded-lg shadow-2xl p-4 max-w-xs w-full text-xs border border-gray-100">
                    <div class="space-y-3">
                        <div class="flex justify-end">
                            <div class="bg-gray-100 rounded-lg rounded-tr-none p-2 max-w-[80%]">
                                <p>Welcome to Second Door PT</p>
                                <p class="text-gray-500 mt-1">Book your appointment</p>
                            </div>
                        </div>
                        <div class="flex justify-start">
                             <div class="bg-primary-50 rounded-lg rounded-tl-none p-3 w-full border border-primary-200">
                                <p class="mb-2 font-medium">Available Times</p>
                                <div class="space-y-1">
                                    <div class="flex items-center gap-2 bg-white p-2 rounded">
                                        <div class="w-3 h-3 bg-primary-500 rounded-sm"></div>
                                        <span>Today 2:00 PM</span>
                                    </div>
                                    <div class="flex items-center gap-2 bg-white p-2 rounded">
                                        <div class="w-3 h-3 border border-gray-300 rounded-sm"></div>
                                        <span>Tomorrow 10:00 AM</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="flex justify-end">
                            <button class="bg-gray-900 text-white px-4 py-2 rounded-full text-[10px]">Confirm Booking</button>
                        </div>
                    </div>
                </div>
            </div>

            <div class="order-1 lg:order-2">
                <h3 class="text-2xl font-heading mb-8">For your patients...</h3>
                <ul class="space-y-8 mb-10">
                    <li class="flex gap-4">
                        <div class="mt-1">{@html Check}</div>
                        <div>
                            <h4 class="font-medium text-gray-900">Easy Scheduling</h4>
                            <p class="text-sm text-gray-600 mt-1">Smart booking rules and digital front door tools make it simple to book appointments.</p>
                        </div>
                    </li>
                    <li class="flex gap-4">
                        <div class="mt-1">{@html Check}</div>
                        <div>
                            <h4 class="font-medium text-gray-900">Better Outcomes</h4>
                            <p class="text-sm text-gray-600 mt-1">Outcomes tracking and NPS surveys ensure quality care delivery.</p>
                        </div>
                    </li>
                    <li class="flex gap-4">
                        <div class="mt-1">{@html Check}</div>
                        <div>
                            <h4 class="font-medium text-gray-900">Stay Engaged</h4>
                            <p class="text-sm text-gray-600 mt-1">Automated re-engagement campaigns keep patients coming back for continued care.</p>
                        </div>
                    </li>
                </ul>
                <a href="#" class="inline-block px-6 py-2.5 rounded-full border border-gray-300 text-sm font-medium hover:bg-gray-50 transition-colors">
                    Learn More
                </a>
            </div>
        </div>
    </div>
</section>
