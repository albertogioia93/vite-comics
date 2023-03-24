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

<style lang="scss" scoped>

header {
    padding: 30px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
</style>