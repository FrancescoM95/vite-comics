<script>
import AppCard from './AppCard.vue';
export default {
    name: 'AppMain',
    props: {
        comics: Array
    },
    components: { AppCard }
}
</script>

<template>
    <main>
        <div class="container">
            <div class="row">
                <AppCard v-for="comic in comics" :key="comic.id" :image="comic.thumb" :title="comic.series" />
            </div>
        </div>
    </main>
</template>

<style lang="scss" scoped>
main {
    background-color: black;
    min-height: calc(100vh - 590px);
    padding-top: 2rem;

    h1 {
        color: #fff;
    }
}

.container {
    max-width: 1180px;
    margin: 0 auto;
}

.row {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}
</style>