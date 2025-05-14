<script lang="ts">
	import { browser } from "$app/environment";
	import { onMount } from "svelte";

 onMount(() => {
    if (browser) {
        window.history.back();
    }
 })


</script>