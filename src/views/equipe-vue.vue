<script>
export default {
    name: 'EquipeView',
    data() {
        return {
            equipe: [
                {
                    nome: 'Kayque',
                },
                {
                    nome: 'Murilo',
                },
                {
                    nome: 'jeffrey',
                },
                {
                    nome: 'Rafael',
                },
                {
                    nome: 'Daniel',
                },
                {
                    nome: 'Arthur',
                },
            ]
        }
    }
}
</script>

<template>
    <div>
        <h1>Equipe</h1>
        <ul>
            <li v-for="membro in equipe" :key="membro.nome">
                <h2>{{ membro.nome }}</h2>
            </li>
        </ul>
    </div>
</template>

<style scoped>
/* Your component-specific styles go here */
</style>