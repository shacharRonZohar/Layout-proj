<template>
    <section class="features-list-container">
        <feature-preview v-for="feature in features" :key="feature.title" :feature="feature" />
    </section>
</template>

<script>
import featurePreview from './feature-preview.vue'
export default {
    components: {
        featurePreview
    },
    data() {
        return {
            features: [
                {
                    title: 'Access your files, anywhere',
                    txt: `The ability to use a smartphone, tablet, or computer to access your account means your files follow you everywhere`
                },
                {
                    title: 'Security you can trust',
                    txt: `2-factor authentication and user-controlled encryption are just a couple of the security features we allow to help secure your files`
                },
                {
                    title: 'Real-time collaboration',
                    txt: `Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.`
                },
                {
                    title: 'Store any type of file',
                    txt: `Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for all file types to be securely stored and shared.`
                },
            ]
        }
    }
}
</script>