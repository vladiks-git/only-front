<template>
    <div class="app">
        <Head></Head>
        <title-company></title-company>
        <welcom></welcom>
        <div class="b-he"></div>
        <main-content></main-content>
        <content2></content2>
        <employeers></employeers>
        <Footer></Footer>
    </div>
</template>

<script>

    import Head from "./components/head";
    import TitleCompany from "./components/title-company";
    import Welcom from "./components/welcom";
    import MainContent from "./components/main-content";
    import Content2 from "./components/content2";
    import Employeers from "./components/employeers";
    import Footer from "./components/footer";
    export default {
        components: {
            Footer,
            Employeers,
            Content2,
            MainContent,
            Welcom,
            TitleCompany,
            Head
        },

    }
</script>

<style scoped>
    .b-he{
        width: auto;
        height: 50px;
        background-color: cadetblue;
    }
</style>
