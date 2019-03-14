<template>
    <header id="header" class="jumbotron jumbotron-fluid text-center d-flex">
        <div class="container-fluid align-self-end">
            <h1 class="display-2">Chelsea Cullen</h1>
            <hr>
            <p class="lead">Actress and Singer | Raleigh, NC</p>
        </div>
    </header>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped lang="scss">
    #header.jumbotron {
        height: calc(100vh - 56px);
        background: url("../assets/images/Cullen_Chelsea_1.jpg") #999 no-repeat top;
        background-size: cover;
        background-attachment: fixed;
        background-blend-mode: screen;
        /*filter: grayscale(50%);*/
        font-weight: 700;
    }
</style>
