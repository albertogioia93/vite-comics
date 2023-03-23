<script>
import AppLogo from './AppLogo.vue';

export default {
    name: 'AppHeader',
    components: {
        AppLogo
    }
}
</script>

<template>
    <header>
        <AppLogo></AppLogo>
        <nav>Menù</nav>
    </header>
</template>

<style scoped></style>