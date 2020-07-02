<template>
    <div class="back">
        <div class="footer">
            <p>Inst: @ershpower</p>
        </div>
    </div>
</template>

<script>
    export default {
        name: "footer"
    }
</script>

<style scoped>
    .footer {
        width: auto;
        height: 200px;
        border: 1px solid black;
        border-radius: 0 0 50px 50px;
        background: rgba(255, 255, 255, 0.5);
    }
    .back{
        background-color: black;
    }
    p{
        display: flex;
        justify-content: center;
        font-size: 100px;
        font-family: Bradley Hand, cursive;
    }
</style>