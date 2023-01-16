<template>
    <li>
        {{ content }}
        <button @click="$emit('delete')">Delete</button>
    </li>
</template>

<script>
export default {
    props: {
        content: String
    }
}
</script>

<style>

</style>