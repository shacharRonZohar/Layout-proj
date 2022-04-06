<template>
    <article class="review-preview">
        <p class="txt">{{ review.txt }}</p>
        <div class="reviewer">
            <div class="avatar" :Style="{ backgroundImage: `url(${review.reviewer.img})` }"></div>
            <span class="name">{{ review.reviewer.name }}</span>
            <small class="position">{{ review.reviewer.position }} {{ review.reviewer.company }}</small>
        </div>
    </article>
</template>

<script>
export default {
    props: {
        review: Object
    }
}
</script>