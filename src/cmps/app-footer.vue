<template>
    <footer class="main-footer-container full">
        <call-to-action />
        <lg-logo />
        <div class="footer">
            <div class="icon location"></div>
            <p
                class="txt"
            >Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe aut quisquam aliquid at fugit mollitia unde nesciunt animi ea</p>

            <contact-us />
            <footer-nav></footer-nav>
            <div class="socials-container">
                <ul class="socials-list">
                    <li class="social-item fb"></li>
                    <li class="social-item twitter"></li>
                    <li class="social-item ig"></li>
                </ul>
            </div>
        </div>
    </footer>
</template>

<script>
import lgLogo from './lg-logo.vue'
import contactUs from './contact-us.vue'
import footerNav from './footer-nav.vue'
import callToAction from './call-to-action.vue'

export default {
    components: {
        lgLogo,
        contactUs,
        footerNav,
        callToAction
    }
}
</script>