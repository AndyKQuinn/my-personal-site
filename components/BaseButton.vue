<script>
// this handling allows our button to adjust from
// being an anchor, href or standard button based
// on what props we pass, or don't pass, to it.
export default {
    props: {
        to: {
            type: String,
        },
        href: {
            type: String,
        },
    },
};
</script>

<template>
    <!-- This switches our style based on the props-->
    <component :is="to ? 'nuxt-link' : href ? 'a' : 'button'" class="">
        <slot></slot>
    </component>
</template>

<style scoped></style>
