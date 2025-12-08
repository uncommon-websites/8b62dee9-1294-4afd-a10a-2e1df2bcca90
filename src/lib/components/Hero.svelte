<script>
	import Button from './Button.svelte';
</script>

<section class="relative overflow-hidden pt-32 pb-20 lg:pt-40 lg:pb-28">
	<div class="mx-auto max-w-7xl px-6">
		<div class="grid grid-cols-1 gap-12 lg:grid-cols-2 lg:gap-8 items-center">
			<!-- Left Content -->
			<div class="max-w-xl">
				<h1 class="font-display text-5xl font-medium leading-[1.1] tracking-tight text-gray-900 sm:text-6xl lg:text-7xl">
					Intelligently connected care
				</h1>
				<p class="mt-6 text-lg leading-relaxed text-gray-600">
					We simplify, automate, and unify care experiences—delivering seamless interactions, reducing care costs, and powering faster, higher quality care at the moment of need.
				</p>
				<div class="mt-8 flex flex-wrap gap-4">
					<Button type="black">
                        Meet Provider Directory <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="ml-2 inline"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
                    </Button>
					<Button type="outline" className="rounded-full border-gray-200">
                        Fabric acquires <span class="font-bold mx-1">gyant</span> <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="ml-2 inline"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
                    </Button>
				</div>
			</div>

			<!-- Right Visual -->
			<div class="relative lg:ml-auto">
                <!-- Peach Background Shape -->
                <div class="absolute -top-10 -right-20 -z-10 h-[500px] w-[500px] rounded-full bg-[#ffddd6]/50 blur-3xl"></div>
                
                <!-- Main UI Card -->
				<div class="relative rounded-2xl bg-white p-6 shadow-2xl border border-gray-100 max-w-md mx-auto lg:mr-0">
                    <div class="flex justify-between items-center mb-6">
                        <h3 class="font-display text-2xl text-gray-900">Your patient's visit summary</h3>
                        <div class="h-8 w-20 bg-blue-100 rounded"></div> <!-- Logo placeholder -->
                    </div>

                    <div class="flex items-center gap-3 mb-6">
                        <div class="h-10 w-10 rounded-full bg-gray-200 overflow-hidden">
                             <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?ixlib=rb-4.0.3&auto=format&fit=crop&w=100&q=80" alt="User" class="h-full w-full object-cover"/>
                        </div>
                        <div>
                            <div class="text-sm font-semibold">Joey Hill</div>
                            <div class="text-xs text-gray-500">Generated on October 2nd</div>
                        </div>
                    </div>

                    <div class="space-y-4">
                        <div class="rounded-xl bg-gray-50 p-4">
                            <h4 class="font-medium text-gray-900 mb-2">Assessment and Treatment Plan</h4>
                            <div class="space-y-2">
                                <div class="h-2 w-3/4 bg-gray-200 rounded"></div>
                                <div class="h-2 w-1/2 bg-gray-200 rounded"></div>
                                <div class="h-2 w-5/6 bg-gray-200 rounded"></div>
                            </div>
                        </div>
                         <div class="rounded-xl bg-gray-50 p-4">
                            <h4 class="font-medium text-gray-900 mb-2">Response to Patient</h4>
                             <div class="space-y-2">
                                <div class="h-2 w-full bg-gray-200 rounded"></div>
                                <div class="h-2 w-4/5 bg-gray-200 rounded"></div>
                            </div>
                        </div>
                    </div>

                    <!-- Floating Notification -->
                    <div class="absolute -bottom-6 -left-12 flex items-center gap-3 rounded-xl bg-white p-3 shadow-lg border border-gray-100">
                        <div class="flex h-8 w-8 items-center justify-center rounded-full bg-green-100 text-green-600">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg>
                        </div>
                        <div class="text-sm font-medium text-gray-900">Patient meets the criteria for<br>antibiotics</div>
                    </div>
				</div>

                <!-- Floating Left Card -->
                 <div class="absolute top-10 -left-16 hidden lg:block rounded-xl bg-white p-4 shadow-xl border border-gray-100 w-48">
                    <div class="text-xs text-gray-500 mb-2">What search did result on this?</div>
                    <div class="flex gap-2">
                         <div class="h-16 w-1/2 bg-gray-50 rounded border border-gray-100 flex items-center justify-center text-xs text-center p-1">No charge</div>
                         <div class="h-16 w-1/2 bg-gray-50 rounded border border-gray-100 flex items-center justify-center text-xs text-center p-1">No hidden costs</div>
                    </div>
                </div>
                 <div class="absolute top-48 -left-10 hidden lg:block rounded-xl bg-white p-4 shadow-xl border border-gray-100 w-56">
                    <div class="text-xs text-gray-500 mb-2">Did the patient's form score match?</div>
                     <div class="h-2 w-full bg-gray-100 rounded mb-1"></div>
                     <div class="h-2 w-2/3 bg-gray-100 rounded"></div>
                </div>

			</div>
		</div>
	</div>
</section>
