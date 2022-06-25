<script>
	export default {
		name: "HeaderMod",
		props: {
			//
		},
	};
</script>

<template>
	<nav>
		<div class="bg-gray-800 text-white text-xl shadow-lg">
			<div class="container py-5 mx-auto px-2 max-w-7xl">
				<router-link to="/">Inicio</router-link>
				<span class="text-gray-500"> | </span>
				<router-link to="/about">Acerca de </router-link>
				<i class="fa-solid fa-heart"></i>
			</div>
		</div>
	</nav>
</template>
