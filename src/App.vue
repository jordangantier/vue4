<script>
	import Header from "@/components/HeaderMod.vue";
	import Footer from "@/components/FooterMod.vue";

	export default {
		name: "AppView",
		components: {
			Header,
			Footer,
		},
	};
</script>

<template>
	<Header message="Header" />
	<router-view />
	<Footer message="Footer" />
</template>
