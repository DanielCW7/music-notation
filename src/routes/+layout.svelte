<script lang="ts">
	import '../app.css';
	
	let { children } = $props();
</script>

<div class="bg-red-200">
	{@render children()}
</div>
