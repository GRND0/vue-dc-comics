<template>
<div>
    <input type="text" placeholder="Ricerca per Serie" v-model="ricerca" >
    <button @click="$emit('searchClick', ricerca)">
        Cerca
    </button>

</div>
</template>

<script>

export default {
    name: "RicercaCustom",
    data: function () {
        return {
            ricerca: "",
        }

    }  
}



</script>

<style>
</style>