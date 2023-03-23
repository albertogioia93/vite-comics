<script>
import AppLogo from './AppLogo.vue';
import AppNav from './AppNav.vue';

export default {
    name: 'AppHeader',
    components: {
        AppLogo,
        AppNav
    }
}
</script>

<template>
    <header>
        <AppLogo></AppLogo>
        <AppNav></AppNav>
    </header>
</template>

<style scoped></style>