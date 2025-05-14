<script lang="ts">
	import { browser } from "$app/environment";
	import { onMount } from "svelte";

 onMount(() => {
    if (browser) {
        // Navigate back in the browser history on mount to return the user to the previous page, as this page is not meant to be accessed directly.
        window.history.back();
    }
 })


</script>