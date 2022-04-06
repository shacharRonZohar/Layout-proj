<template>
    <article class="feature-preview-container">
        <div class="img-container">
            <img :src="`${feature.img}`" />
        </div>
        <h3 class="title">{{ feature.title }}</h3>
        <p class="txt">{{ feature.txt }}</p>
    </article>
</template>        
<script>
export default {
    props: {
        feature: Object
    }
}
</script>