<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>
<template>
    <nav class="bg-red">
        <RouterLink to="/">Accueil</RouterLink>
		<RouterLink to="/agents">Agents</RouterLink>
        <RouterLink to="/armes">Armes</RouterLink>
        <RouterLink to="/maps">Maps</RouterLink>
    </nav>
</template>