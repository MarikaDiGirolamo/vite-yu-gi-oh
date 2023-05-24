<script>
export default {
    name: "AppComponent",
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
    <main>
        <div class="container">
            <select name="" id="choose">
                <option value="1">Mazzo Mostro</option>
                <option value="2">Carte Magia</option>
                <option value="3">Carte Trappola</option>
            </select>

        </div>

    </main>
</template>

<style lang="scss" scoped>
main {
    background-color: goldenrod;

    #choose {
        margin: 0.5rem;
        padding: 0.5rem;
        border-radius: 20px;
    }
}
</style>