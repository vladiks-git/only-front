<template>
    <div class="h-div">
        <uL>
            <li>
                <div>
                    <p>content</p>
                </div>
            </li>
            <li>
                <div >
                    <p>content</p>
                </div>
            </li>
            <li>
                <div>
                    <p>content</p>
                </div>
            </li>
            <li>
                <div>
                    <p>content</p>
                </div>
            </li>
        </uL>
    </div>
</template>

<script>
    export default {
        name: "head"
    }
</script>

<style scoped>
    ul{
        display: flex;
        justify-content: center;
    }
    ul li{
        list-style-type: none;
        margin-right: 80px;
        margin-left: 80px;
        margin-top: -5px;
    }
    ul li div{
        border-radius: 0 0 7px 7px;
        width: auto;
        height: 55px;
    }
    ul li div p{
        padding: 15px;
        text-align: center;
    }
    ul li div:hover{
        background-color: cadetblue;
    }
    .h-div{
        width: auto;
        height: 45px;
        background-image: url("https://365psd.ru/images/backgrounds/bg-lightl-901.jpg");
    }
</style>