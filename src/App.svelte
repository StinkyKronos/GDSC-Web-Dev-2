<script>
    import Style1 from "./navbars/style1.svelte";
    import Style2 from "./navbars/style2.svelte";
	import Style3 from "./navbars/style3.svelte";
	import Style4 from "./navbars/style4.svelte";
	import Style5 from "./navbars/style5.svelte";

    let selected = 'Style1'

    let options = [
        'Style1',
        'Style2',
        'Style3',
        'Style4',
        'Style5',
    ]
</script>

{#if selected==='Style1'}
    <Style1 />
{:else if selected==='Style2'}
    <Style2 />
{:else if selected==='Style3'}
    <Style3 />
{:else if selected==='Style4'}
    <Style4 />
{:else if selected==='Style5'}
    <Style5 />
{/if}
    


<div class="layout-selector">
    <div class="text">Pick the style you want:</div>
    <select bind:value={selected}>
        {#each options as value}<option {value}>{value}</option>{/each}
    </select>
</div>