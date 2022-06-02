<template>
	<div class="entry-container mb-3 pointer p-2" @click="$router.push({ name: 'entry', params: { id: 10 } })">

		<!-- Título -->
		<div class="entry-title d-flex">
			<span class="text-success fs-5 fw-bold">15</span>
			<span class="mx-1 fs-5">Julio</span>
			<span class="mx-1 fw-light">2021, jueves</span>
		</div>

		<div class="entry-description">
			Magna labore elit sit consectetur. Ex reprehenderit cillum esse dolore voluptate reprehenderit. Laborum aute ex culpa dolore est ex quis dolore ipsum nostrud velit minim. Id sit culpa commodo voluptate est consequat proident eu id consequat exercitation do fugiat non.
		</div>
	</div>
</template>

<style lang="scss" scoped>
.entry-container{
	border-bottom: 1px solid #2c3e50;
	transition: 0.2s all easy-in;

	&:hover{
		background-color: lighten($color: grey, $amount: 40);
		transition: 0.2s all easy-in;
	}

	.entry-description{
		font-size: 12px;
	}
}
</style>