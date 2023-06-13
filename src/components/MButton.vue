<script setup>
const props = defineProps({
    text: String
})

</script>
<template>
    <button>{{ props.text }}</button>
</template>

<style scoped>
button{
    background-color: blue;
    padding: 15px;
    border: 5px solid lightblue;
    border-radius: 8px;
    color: white;
    font-size: 1.1rem;
    margin: 0 5px;
    cursor: pointer;
}
button:hover{
    background-color: darkblue;
}

</style>