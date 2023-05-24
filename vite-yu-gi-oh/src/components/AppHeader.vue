<script>
export default {
    name: "AppHeader",
    components: {

    },
    data() {
        return {

        }
    },
    methods: {

    },
    mounted() {

    }
}
</script>

<template>
    <header>
        <img src="../assets/Yu-Gi-Oh!_(Logo).jpg" alt="Logo" width="100" height="40">
        <h1>Yu-Gi-Oh API</h1>

    </header>
</template>

<style lang="scss" scoped>
@use '../styles/general.scss' as *;

header {
    background-color: whitesmoke;
    display: flex;
    // align-items: flex-start;
    padding: 1rem;

    h1 {
        margin-left: 20px;
        font-size: 3rem;
    }
}
</style>