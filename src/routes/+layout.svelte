<script>
	import '../app.css';
	import Header from './Header.svelte';
	import Nav from './Nav.svelte';
</script>

<Nav />
<Header />
<slot><!-- optional fallback --></slot>

<!-- the footer is not included on this page because it needs to use the
        background color of the nested layout -->
