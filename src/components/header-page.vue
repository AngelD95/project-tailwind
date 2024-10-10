<template>
	<header class="relative py-8">
		<div class="w-full h-14 max-w-7xl mx-auto m-0 flex justify-between items-center">
			<div class="text-2xl font-bold">
				<a class="no-underline text-juniper-200 hover:text-bull-shot-200" href="#">Web Dev Creative</a>
			</div>
			<ul class="flex gap-4">
				<li><a class="no-underline text-juniper-200 text-base hover:text-bull-shot-200" href="home">Home</a></li>
				<li><a class="no-underline text-juniper-200 text-base hover:text-bull-shot-200" href="about">About</a></li>
				<li><a class="no-underline text-juniper-200 text-base hover:text-bull-shot-200" href="services">Services</a></li>
				<li><a class="no-underline text-juniper-200 text-base hover:text-bull-shot-200" href="contant">Contact</a></li>
			</ul>
			<a href="#" class="action_btn bg-bull-shot-300 text-juniper-100 py-2 px-4 border-0 outline-0 rounded-3xl text-sm font-bold cursor-pointer transition scale ease-in-out duration-200
				hover:scale-105
				active:scale-95">Get Started</a>
			<div class="text-2xl text-white cursor-pointer 2xl:hidden xl:hidden md:hidden sm:block">
				<i class="fas fa-bars"></i>
			</div>
		</div>
	</header>
</template>

<script>
	export default {
		name: 'header-page',
	};
</script>

<style lang="scss" scoped>

</style>