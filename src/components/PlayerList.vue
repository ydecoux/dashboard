<template>
    <div>
        <div v-for="player in players" v-bind:key="player.id">
            {{player.name}}
        </div>
    </div>
</template>

<script>
export default {
    name:'PlayerList',
    data: function () {
        return {
            players:[{
            id:'123',
            name: 'Foo',
            score: 45
        },{
            id:'456',
            name: 'Bar',
            score: 14
        },{
            id:'789',
            name: 'Baz',
            score: 43
        },
        ]}
    }
}
</script>

<style>

</style>
