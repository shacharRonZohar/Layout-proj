<template>
    <section class="reviews-list-container">
        <!-- {{ reviews }} -->
        <review-preview v-for="review in reviews" :key="review.title" :review="review"></review-preview>
    </section>
</template>

<script>
import reviewPreview from './review-preview.vue'
export default {
    components: {
        reviewPreview
    },
    data() {
        return {
            reviews: [
                {
                    txt: `Fylo has improved our team productivity by an order of magnitue. Since making the switch our team has become a well-oiled collaboration machine.`,
                    reviewer: {
                        name: 'Satish Patel',
                        position: 'Founder & CEO',
                        company: 'Huddle',
                        img: './src/assets/imgs/profile-1.jpg'
                    }
                },
                {
                    txt: `Fylo has improved our team productivity by an order of magnitue. Since making the switch our team has become a well-oiled collaboration machine.`,
                    reviewer: {
                        name: 'Bruce McKenzie',
                        position: 'Founder & CEO',
                        company: 'Huddle',
                        img: './src/assets/imgs/profile-2.jpg'
                    }
                },
                {
                    txt: `Fylo has improved our team productivity by an order of magnitue. Since making the switch our team has become a well-oiled collaboration machine.`,
                    reviewer: {
                        name: 'Ive Boyd',
                        position: 'Founder & CEO',
                        company: 'Huddle',
                        img: './src/assets/imgs/profile-3.jpg'
                    }
                }
            ]
        }
    }
}
</script>