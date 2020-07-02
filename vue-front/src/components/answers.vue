<template>
    <div class="answer">
        <img class="img-user" src="https://static.thenounproject.com/png/17241-200.png">
        <p class="author">Author</p>
        <div class="time">Something content</div>
   </div>
</template>

<script>
    export default {
        name: "answers"
    }
</script>

<style scoped>
    .answer{
        height: 160px;
        width: 400px;
        border-bottom: 5px solid darkgrey;
        border-radius: 10px;
    }
    .img-user{
        width: 100px;
        height: 100px;
        margin-left: 5px;
        margin-top: 5px;
        float:left;
    }
    .author{
        font-family: Marker Felt, fantasy;
        font-size: 35px;
        padding-top: 30px;
        margin-left: 15px;
    }
    .time{
        clear: none;
        margin-top: 36px;
        margin-left: 10px;
        color: white;
    }
</style>