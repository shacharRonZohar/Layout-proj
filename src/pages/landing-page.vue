<template>
    <main class="landing-page-container">
        <app-hero></app-hero>
        <!-- <features-list></features-list>
        <bottom-content></bottom-content>
        <reviews-list></reviews-list>
        <call-to-action></call-to-action>-->
    </main>
</template>

<script>
import appHero from '../cmps/app-hero.vue'
import featuresList from '../cmps/features-list.vue'
import bottomContent from '../cmps/bottom-content.vue'
import reviewsList from '../cmps/reviews-list.vue'
import callToAction from '../cmps/call-to-action.vue'
export default {
    components: {
        appHero,
        featuresList,
        bottomContent,
        reviewsList,
        callToAction

    }
}
</script>