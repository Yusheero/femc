<script setup lang="ts">
import HeaderComponent from "./components/header/header-component.vue";
import MainComponent from "./components/main/main-component.vue";
import FooterComponent from "./components/footer/footer-component.vue";
</script>

<template>
	<div class="app-wrapper">
		<HeaderComponent />
		<MainComponent />
		<FooterComponent />
	</div>
</template>

<style scoped>
.app-wrapper {
	display: flex;
	flex-direction: column;
}
</style>
