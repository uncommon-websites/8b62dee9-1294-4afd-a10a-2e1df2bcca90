<script lang="ts">
    const Check = `<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-gray-400"><path fill-rule="evenodd" d="M19.916 4.626a.75.75 0 0 1 .208 1.04l-9 13.5a.75.75 0 0 1-1.154.114l-6-6a.75.75 0 0 1 1.06-1.06l5.353 5.353 8.493-12.74a.75.75 0 0 1 1.04-.207Z" clip-rule="evenodd" /></svg>`;
</script>

<section class="py-24">
    <div class="max-w-[1440px] mx-auto px-6">
        <h2 class="text-4xl md:text-5xl font-heading mb-20 max-w-3xl">
            Deliver seamless experiences and faster, higher-quality care at the moment of need
        </h2>

        <!-- Section 1: Clinicians -->
        <div class="grid lg:grid-cols-2 gap-16 mb-32 items-center">
            <div>
                <h3 class="text-2xl font-heading mb-8">For clinicians...</h3>
                <ul class="space-y-8 mb-10">
                    <li class="flex gap-4">
                        <div class="mt-1">{@html Check}</div>
                        <div>
                            <h4 class="font-medium text-gray-900">Move Faster</h4>
                            <p class="text-sm text-gray-600 mt-1">With automated symptom collection, documentation, prescriptions, and lab orders.</p>
                        </div>
                    </li>
                    <li class="flex gap-4">
                        <div class="mt-1">{@html Check}</div>
                        <div>
                            <h4 class="font-medium text-gray-900">Work smarter</h4>
                            <p class="text-sm text-gray-600 mt-1">Thanks to readily available, evidence-based decision support.</p>
                        </div>
                    </li>
                    <li class="flex gap-4">
                        <div class="mt-1">{@html Check}</div>
                        <div>
                            <h4 class="font-medium text-gray-900">Care better</h4>
                            <p class="text-sm text-gray-600 mt-1">Optimize resource allocation and patient flow.</p>
                        </div>
                    </li>
                </ul>
                <a href="#" class="inline-block px-6 py-2.5 rounded-full border border-gray-300 text-sm font-medium hover:bg-gray-50 transition-colors">
                    Request a demo
                </a>
            </div>
            
            <div class="relative">
                <img src="https://images.unsplash.com/photo-1551884170-09fb70a3a2ed?q=80&w=2000&auto=format&fit=crop" alt="Clinician smiling" class="rounded-lg shadow-xl w-full max-w-md ml-auto object-cover h-[500px]" />
                
                <!-- Floating UI Card -->
                <div class="absolute top-10 left-0 bg-white rounded-lg shadow-2xl p-4 max-w-xs w-full text-xs border border-gray-100">
                    <div class="mb-3 pb-3 border-b">
                        <p class="text-gray-500 mb-1">Melanie (34) attests to experiencing abdominal pain</p>
                    </div>
                    <div class="mb-3">
                        <p class="font-medium mb-2">Recommended diagnoses</p>
                        <div class="flex items-center gap-2 mb-1">
                            <div class="w-3 h-3 bg-black rounded-sm"></div>
                            <div class="h-2 bg-gray-200 rounded w-24"></div>
                        </div>
                        <div class="flex items-center gap-2">
                            <div class="w-3 h-3 border rounded-sm"></div>
                            <div class="h-2 bg-gray-100 rounded w-20"></div>
                        </div>
                    </div>
                    <div>
                        <p class="font-medium mb-2">Discharge patient</p>
                        <div class="bg-gray-50 p-2 rounded mb-2">
                            <p class="text-[10px] text-gray-500">Dear Melanie,</p>
                            <div class="h-1 bg-gray-200 rounded w-full my-1"></div>
                            <div class="h-1 bg-gray-200 rounded w-2/3"></div>
                        </div>
                        <button class="w-full bg-[#1a2c38] text-white py-1.5 rounded text-[10px]">Send care plan and begin discharge</button>
                    </div>
                </div>
            </div>
        </div>

        <!-- Section 2: Consumers -->
        <div class="grid lg:grid-cols-2 gap-16 items-center">
            <div class="order-2 lg:order-1 relative">
                <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?q=80&w=2000&auto=format&fit=crop" alt="Man on couch" class="rounded-lg shadow-xl w-full max-w-md object-cover h-[500px]" />
                
                <!-- Floating UI Card -->
                <div class="absolute bottom-20 right-0 bg-white rounded-lg shadow-2xl p-4 max-w-xs w-full text-xs border border-gray-100">
                    <div class="space-y-3">
                        <div class="flex justify-end">
                            <div class="bg-gray-100 rounded-lg rounded-tr-none p-2 max-w-[80%]">
                                <p>Welcome, Melanie</p>
                                <p class="text-gray-500 mt-1">Please start your intake</p>
                            </div>
                        </div>
                        <div class="flex justify-end">
                            <button class="bg-black text-white px-3 py-1 rounded-full text-[10px]">Get started</button>
                        </div>
                        <div class="flex justify-start">
                             <div class="bg-gray-50 rounded-lg rounded-tl-none p-3 w-full border border-gray-100">
                                <p class="mb-2">Was the onset of abdominal pain sudden?</p>
                                <div class="space-y-1">
                                    <div class="flex items-center gap-2">
                                        <div class="w-3 h-3 bg-black rounded-sm"></div>
                                        <span>Yes</span>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <div class="w-3 h-3 border rounded-sm"></div>
                                        <span>No</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="flex justify-start">
                             <div class="bg-gray-50 rounded-lg rounded-tl-none p-3 w-full border border-gray-100">
                                <p>Where is your preferred pharmacy?</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="order-1 lg:order-2">
                <h3 class="text-2xl font-heading mb-8">For consumers...</h3>
                <ul class="space-y-8 mb-10">
                    <li class="flex gap-4">
                        <div class="mt-1">{@html Check}</div>
                        <div>
                            <h4 class="font-medium text-gray-900">Start anywhere</h4>
                            <p class="text-sm text-gray-600 mt-1">Gain digital-first access to care wherever and whenever.</p>
                        </div>
                    </li>
                    <li class="flex gap-4">
                        <div class="mt-1">{@html Check}</div>
                        <div>
                            <h4 class="font-medium text-gray-900">Know more</h4>
                            <p class="text-sm text-gray-600 mt-1">With simple step-by-step guides across the journey.</p>
                        </div>
                    </li>
                    <li class="flex gap-4">
                        <div class="mt-1">{@html Check}</div>
                        <div>
                            <h4 class="font-medium text-gray-900">Stay connected</h4>
                            <p class="text-sm text-gray-600 mt-1">Through sleek experiences that keep them happy and coming back.</p>
                        </div>
                    </li>
                </ul>
                <a href="#" class="inline-block px-6 py-2.5 rounded-full border border-gray-300 text-sm font-medium hover:bg-gray-50 transition-colors">
                    Request a demo
                </a>
            </div>
        </div>
    </div>
</section>
