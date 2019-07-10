<template>
    <header id="header" class="jumbotron jumbotron-fluid text-center d-flex">
        <div class="container align-self-end">
            <div class="col-lg-10 col-md-12 mx-auto">
                <h1 class="display-2">Chelsea Cullen</h1>
                <hr>
                <p class="lead">Actress and Singer | Raleigh, NC</p>
            </div>
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
        background: url("../../public/images/cc1.jpg") #999 no-repeat center 30%;
        background-size: cover;
        background-blend-mode: screen;
        font-weight: 700;
    }
</style>
