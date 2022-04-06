<template>
    <main class="landing-page-container full">
        <app-hero />
        <features-list />
        <bottom-content />
        <!-- Was almost done with it but it fucked up my layout and was out of time -->
        <reviews-list />
        <call-to-action />
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