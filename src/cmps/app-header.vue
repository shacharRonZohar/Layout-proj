<template>
    <header class="app-header-container">
        <lg-logo></lg-logo>
        <main-nav></main-nav>
    </header>
</template>

<script>
import lgLogo from './lg-logo.vue'
import mainNav from './main-nav.vue'

export default {
    components: {
        lgLogo,
        mainNav
    }
}
</script>