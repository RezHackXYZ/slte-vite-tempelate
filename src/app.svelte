<script>
	import Router from "svelte-spa-router";
	import { location } from "svelte-spa-router";
	import Home from "./pages/home/home.svelte";

	let routes = {
		"/": Home,
	};
</script>

<Router {routes} />
