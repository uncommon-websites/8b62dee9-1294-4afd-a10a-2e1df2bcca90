<script>
	export let type = 'primary'; // primary, secondary, outline, ghost, black
	export let href = '';
	export let icon = null;
    export let className = '';
</script>

{#if href}
	<a
		{href}
		class="inline-flex items-center justify-center rounded-full px-6 py-3 text-sm font-medium transition-colors duration-200 {className}
        {type === 'primary' ? 'bg-[#b0ccfc] text-gray-900 hover:bg-[#9bbef9]' : ''}
        {type === 'black' ? 'bg-gray-900 text-white hover:bg-gray-800' : ''}
        {type === 'outline' ? 'border border-gray-300 bg-white text-gray-900 hover:bg-gray-50' : ''}
        {type === 'ghost' ? 'text-gray-600 hover:text-gray-900' : ''}"
	>
		<slot />
		{#if icon}
			<span class="ml-2">{icon}</span>
		{/if}
	</a>
{:else}
	<button
		class="inline-flex items-center justify-center rounded-full px-6 py-3 text-sm font-medium transition-colors duration-200 {className}
        {type === 'primary' ? 'bg-[#b0ccfc] text-gray-900 hover:bg-[#9bbef9]' : ''}
        {type === 'black' ? 'bg-gray-900 text-white hover:bg-gray-800' : ''}
        {type === 'outline' ? 'border border-gray-300 bg-white text-gray-900 hover:bg-gray-50' : ''}
        {type === 'ghost' ? 'text-gray-600 hover:text-gray-900' : ''}"
	>
		<slot />
		{#if icon}
			<span class="ml-2">{icon}</span>
		{/if}
	</button>
{/if}
