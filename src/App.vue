<template>
    <div id="app" class="container-fluid">
        <Nav></Nav>
        <Header></Header>
        <Reel></Reel>
        <Gallery></Gallery>
        <Contact></Contact>
        <Footer></Footer>
    </div>
</template>

<script>
    import Nav from './components/Nav'
    import Header from './components/Header'
    import Gallery from './components/Gallery'
    import Reel from './components/Reel'
    import Contact from './components/Contact'
    import Footer from './components/Footer'

    export default {
        name: 'app',
        components: {
            Nav, Header, Reel, Contact, Footer, Gallery
        }
    }
</script>

<style lang="scss">
    @import url("https://use.typekit.net/dml3adt.css");
    @import "../public/styles/style.scss";

    #app {
        font-family: termina,sans-serif;
        font-weight: 400;
        font-style: normal;
    }

    .iframe-container {
        position: relative;
        width: 100%;
        padding-bottom: 56.25%;
        height: 0;

        iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
    }
</style>
