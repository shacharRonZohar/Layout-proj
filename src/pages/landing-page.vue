<template>
    <main class="landing-page-container full">
        <app-hero />
        <features-list />
        <bottom-content />
        <reviews-list />
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