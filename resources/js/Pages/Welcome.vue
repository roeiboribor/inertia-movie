<template>
    <h1>Hello {{ name }}</h1>

    <p>In this series, we will use the following frameworks:</p>
    <ul>
        <li
            v-bind:key="framework"
            v-for="framework of frameworks"
            v-text="framework"
        />
    </ul>
    <Nav />
</template>
<script>
import Nav from "../Shared/Nav.vue";

export default {
    components: { Nav },
    props: {
        name: String,
        frameworks: Array,
    },
};
</script>
