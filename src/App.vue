<template>
    <div id="example">
        <h1>{{ msg }}</h1>
    </div>
</template>

<script>
export default {
    data () {
        return {
            msg: 'Hello World!'
        }
    }
}
</script>

<style scoped>
#example {
    height: 100px;
    width: 400px;
    font-size: 24px;
    background-color: lightblue;
    text-align: center;
}
</style>