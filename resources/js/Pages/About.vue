<template>
    <div>
        <h1>Sobre nós</h1>
        <h2>Olá, {{ name }}</h2>
        <h2>Estou fazendo curso de {{ curso}}</h2>
    </div>
</template>

<script>
export default {
    name: 'PageAbout',

    props: {
        name: String,
        curso: String
    },
}
</script>

<style lang="scss" scoped>

</style>