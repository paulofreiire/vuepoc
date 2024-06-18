<script setup>
</script>

<template>
	<div class="collapse navbar-collapse" id="navbar-menu">
		<div>
			<form action="./" method="get" autocomplete="off" novalidate="true">
	            <div class="input-icon">
	                <span class="input-icon-addon">
	                    <!-- Download SVG icon from http://tabler-icons.io/i/search -->
	                    <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"></path><path d="M10 10m-7 0a7 7 0 1 0 14 0a7 7 0 1 0 -14 0"></path><path d="M21 21l-6 -6"></path></svg>
	                </span>
	                <input type="text" value="" class="form-control" placeholder="Search…" aria-label="Search in website">
	            </div>
	        </form>
	    </div>
	</div>
</template>

<style scoped>
	#navbar-menu {
		margin-left: 150px
	}
</style>

