<template>
    <div class="w-block">
        <div class="sec-block">
            <h2>This site is only for testing.</h2>
            <button class="btn-go">Ok! Let`s go!</button>
        </div>
    </div>
</template>

<script>
    export default {
        name: "welcom"
    }
</script>

<style scoped>
    .w-block{
        width: auto;
        height: 620px;
        background: linear-gradient(to right, chocolate, aquamarine);
        opacity: 0.80;
        position: relative;
    }
    .sec-block{
        height: 400px;
        width: auto;
        background-image: url("https://i.pinimg.com/originals/f1/14/31/f11431776fc32685f06b9da0e377dd1b.jpg");
        position: absolute;
        top: 0;
        right: 0;
        bottom: 0;
        left: 0;
        margin: auto;
    }
    div h2 {
        color: white;
        text-align: center;
        padding: 8rem 0 0 0;
    }
    .btn-go{
        width: 12rem;
        height: 4rem;
        margin-left: 48rem;
        margin-top: 8px;
        border-radius: 5px;
        background: rgba(255, 255, 255, 0.5);
    }
    .btn-go:hover{
        background-color: green;
        opacity: 85;
        border: #FFFFFF;
    }

</style>