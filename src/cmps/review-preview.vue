<template>
    <article class="review-preview">
        <p class="txt">{{ review.txt }}</p>
        <div class="reviewer">
            <div class="avatar" :style="{ backgroundImage: `url(${review.reviewer.img})` }"></div>
            <div class="details">
                <span class="name">{{ review.reviewer.name }}</span>

                <span
                    class="position"
                >&nbsp {{ review.reviewer.position }}, {{ review.reviewer.company }}</span>
            </div>
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