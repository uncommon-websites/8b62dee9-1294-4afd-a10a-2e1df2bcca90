<script>
	import Button from './Button.svelte';
</script>

<section class="relative overflow-hidden pt-32 pb-20 lg:pt-40 lg:pb-28">
	<div class="mx-auto max-w-7xl px-6">
		<div class="grid grid-cols-1 gap-12 lg:grid-cols-2 lg:gap-8 items-center">
			<!-- Left Content -->
			<div class="max-w-xl">
				<h1 class="font-display text-5xl font-medium leading-[1.1] tracking-tight text-gray-900 sm:text-6xl lg:text-7xl">
					Transform your PT practice with direct employer contracts
				</h1>
				<p class="mt-6 text-lg leading-relaxed text-gray-600">
					Second Door helps physical therapy practices convert to direct-pay models through employer contracts and subscription automation. Capture your share of the $50B MSK market with the tools you need to succeed.
				</p>
				<div class="mt-8 flex flex-wrap gap-4">
					<Button type="black">
                        Get Started Today <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="ml-2 inline"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
                    </Button>
					<Button type="outline" className="rounded-full border-gray-200">
                        View Pricing <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="ml-2 inline"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
                    </Button>
				</div>
			</div>

			<!-- Right Visual -->
			<div class="relative lg:ml-auto">
                <!-- Teal Background Shape -->
                <div class="absolute -top-10 -right-20 -z-10 h-[500px] w-[500px] rounded-full bg-primary-200/40 blur-3xl"></div>
                
                <!-- Main UI Card -->
				<div class="relative rounded-2xl bg-white p-6 shadow-2xl border border-gray-100 max-w-md mx-auto lg:mr-0">
                    <div class="flex justify-between items-center mb-6">
                        <h3 class="font-display text-xl text-gray-900">Employer Discovery</h3>
                        <div class="px-3 py-1 bg-primary-100 text-primary-700 rounded-full text-xs font-medium">Active</div>
                    </div>

                    <div class="space-y-4 mb-6">
                        <div class="rounded-xl bg-gray-50 p-4 border border-gray-200">
                            <div class="flex items-center justify-between mb-3">
                                <h4 class="font-medium text-gray-900 text-sm">Local Employers</h4>
                                <span class="text-xs text-gray-500">24 matches</span>
                            </div>
                            <div class="space-y-2">
                                <div class="flex items-center gap-2">
                                    <div class="h-8 w-8 bg-gray-200 rounded"></div>
                                    <div class="flex-1">
                                        <div class="h-2 w-3/4 bg-gray-300 rounded mb-1"></div>
                                        <div class="h-2 w-1/2 bg-gray-200 rounded"></div>
                                    </div>
                                </div>
                                <div class="flex items-center gap-2">
                                    <div class="h-8 w-8 bg-gray-200 rounded"></div>
                                    <div class="flex-1">
                                        <div class="h-2 w-2/3 bg-gray-300 rounded mb-1"></div>
                                        <div class="h-2 w-1/3 bg-gray-200 rounded"></div>
                                    </div>
                                </div>
                            </div>
                        </div>
                         <div class="rounded-xl bg-primary-50 p-4 border border-primary-200">
                            <h4 class="font-medium text-gray-900 mb-2 text-sm">Campaign Performance</h4>
                             <div class="grid grid-cols-2 gap-3">
                                <div>
                                    <div class="text-2xl font-bold text-gray-900">47%</div>
                                    <div class="text-xs text-gray-600">Open Rate</div>
                                </div>
                                <div>
                                    <div class="text-2xl font-bold text-gray-900">12</div>
                                    <div class="text-xs text-gray-600">Responses</div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Floating Notification -->
                    <div class="absolute -bottom-6 -left-12 flex items-center gap-3 rounded-xl bg-white p-3 shadow-lg border border-gray-100">
                        <div class="flex h-8 w-8 items-center justify-center rounded-full bg-green-100 text-green-600">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg>
                        </div>
                        <div class="text-sm font-medium text-gray-900">3 new employer leads<br>this week</div>
                    </div>
				</div>

                <!-- Floating Left Card -->
                 <div class="absolute top-10 -left-16 hidden lg:block rounded-xl bg-white p-4 shadow-xl border border-gray-100 w-48">
                    <div class="text-xs text-gray-500 mb-2">Revenue Growth</div>
                    <div class="flex items-end gap-1 h-16">
                         <div class="w-1/4 bg-primary-200 rounded-t"></div>
                         <div class="w-1/4 bg-primary-300 rounded-t h-3/4"></div>
                         <div class="w-1/4 bg-primary-400 rounded-t h-4/5"></div>
                         <div class="w-1/4 bg-primary-500 rounded-t h-full"></div>
                    </div>
                    <div class="text-xs text-gray-600 mt-2">↑ 34% this quarter</div>
                </div>
                 <div class="absolute top-48 -left-10 hidden lg:block rounded-xl bg-white p-4 shadow-xl border border-gray-100 w-56">
                    <div class="text-xs text-gray-500 mb-2">EMR Integration Status</div>
                     <div class="flex items-center gap-2 mb-2">
                        <div class="h-2 w-2 bg-green-500 rounded-full"></div>
                        <span class="text-xs text-gray-700">Connected & Syncing</span>
                     </div>
                     <div class="text-xs text-gray-500">Last sync: 2 minutes ago</div>
                </div>

			</div>
		</div>
	</div>
</section>
