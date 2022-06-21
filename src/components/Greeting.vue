<template>
     <p>{{ msg }}</p>
</template>

<script>
export default {
    name: "Greeting-Example",
    data() {
        return {
            msg: "Hello world!",
        };
    },
};
</script>

<style scoped lang="scss">
$color: red;

p {
    color: $color;
}
</style>