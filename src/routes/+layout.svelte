<script lang="ts">
	import './layout.css';

	const { children } = $props();
</script>

<nav class="site-nav">
	<a href="/">Home</a>
	<a href="/stories">Stories</a>
</nav>

{@render children()}
