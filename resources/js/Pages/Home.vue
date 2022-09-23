<template>
    <table class="table table-hover table-striped">
        <thead>
            <tr>
                <th scope="col">ID</th>
                <th scope="col">Título</th>
                <th scope="col">Descrição</th>
            </tr>
        </thead>
        <tbody>
            <tr v-for="post in posts" :key="post.id">
                <th scope="row">{{ post.id }}</th>
                <td>{{ post.title }}</td>
                <td>{{ post.content }}</td>
            </tr>
        </tbody>
    </table>
</template>

<script>
export default {
    name: 'PageHome',

    props: {
        posts: Object
    },

}
</script>

<style lang="scss" scoped>

</style>