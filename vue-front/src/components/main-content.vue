<template>
    <div>
        <div class="circle">
            <p>Content</p>
        </div>
        <div class="circle">
            <p>Content</p>
        </div>
        <div class="circle">
            <p>Content</p>
        </div>
        <div class="circle">
            <p>Content</p>
        </div>
    </div>
</template>

<script>
    export default {
        name: "main-content"
    }
</script>

<style scoped>
    .circle{
        display: inline-block;
        margin-top: 80px;
        margin-left: 180px;
        border-radius: 50%;
        height: 200px;
        width: 200px;
        position: relative;
        background-color: burlywood;
        transition: background-color 500ms linear;
    }
    .circle:hover{
        background-color: black;
    }
    p{
        font-size: 25px;
        position: absolute;
        top:50%;
        left: 50%;
        transform: translate(-50%, -50%);
        transition: color 500ms linear;
    }
    .circle:hover p{
        color: white;
        text-shadow: 0 0 5px #FFF, 0 0 10px #FFF, 0 0 15px #FFF, 0 0 20px #49ff18, 0 0 30px #49FF18, 0 0 40px #49FF18, 0 0 55px #49FF18, 0 0 75px #49ff18;
    }

</style>