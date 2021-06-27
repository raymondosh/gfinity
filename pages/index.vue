<template>
	<div class="container">
		<div class="flex flex-col items-center">
			<img src="~/assets/images/gfinity-logo.png" alt="gfinity-logo" />
			<dummy-component></dummy-component>
			<div class="links">
				<a
					href="https://nuxtjs.org/"
					target="_blank"
					class="button--green"
				>
					Documentation
				</a>
				<a
					href="https://github.com/nuxt/nuxt.js"
					target="_blank"
					class="button--grey"
				>
					GitHub
				</a>
			</div>
		</div>
	</div>
</template>
<script>
import DummyComponent from '~/components/dummy-component'

export default {
	components: {
		DummyComponent
	}
}
</script>
<style>
.container {
	margin: 0 auto;
	min-height: 100vh;
	display: flex;
	justify-content: center;
	align-items: center;
	text-align: center;
}

.button--green {
	display: inline-block;
	border-radius: 4px;
	border: 1px solid #3b8070;
	color: #3b8070;
	text-decoration: none;
	padding: 10px 30px;
}

.button--green:hover {
	color: #fff;
	background-color: #3b8070;
}

.button--grey {
	display: inline-block;
	border-radius: 4px;
	border: 1px solid #35495e;
	color: #35495e;
	text-decoration: none;
	padding: 10px 30px;
	margin-left: 15px;
}

.button--grey:hover {
	color: #fff;
	background-color: #35495e;
}
</style>
