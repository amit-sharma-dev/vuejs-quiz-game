<template>
    <section class="score">
        Player <span>{{ this.correctCount }}</span> X <span>{{ this.wrongCount }}</span> Computer
    </section>
</template>

<script>
    export default {
        props: ['correctCount', 'wrongCount']
    }
</script>

<style lang="scss">
    section.score {
        border-bottom: 1px solid black;
        padding: 24px;
        font-size: 18px;
        span {
            padding: 8px;
            font-weight: bold;
            border: 1px solid black;
        }
    }
    section {
        display: block;
    }
</style>