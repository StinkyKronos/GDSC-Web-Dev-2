<script>
	import Search from "../components/search.svelte";
	import Lists from "../components/lists.svelte";
	import Logo from "../components/logo.svelte";
</script>

<style>
    .left, .right {
        display: flex;
        align-items: center;
        gap: 30px;
    }
</style>

<div class="nav-container">
    <div class="left">
        <Logo />
        <Search />
    </div>
    
    <div class="right">
        <Lists />
    </div>
</div>