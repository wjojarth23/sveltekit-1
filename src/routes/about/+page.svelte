
<script>
	import { onMount } from "svelte";
	import { writable } from "svelte/store";

	import { browser } from '$app/environment';
	import { page } from '$app/stores';
  
	onMount( () => {
	  //let hashParams = $page.url.searchParams;
	  console.log("mounted")
	});
</script>
<div>hello world</div>