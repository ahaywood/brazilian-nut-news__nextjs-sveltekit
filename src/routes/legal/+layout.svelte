<script lang="ts">
	import Footer from '$lib/components/Footer.svelte';
</script>

<div class="legal-content bg-icterine">
	<slot><!-- optional fallback --></slot>
	<div class="border-t-2 border-t-cinder py-8 pl-leftGutter text-black">
		<Footer />
	</div>
</div>
