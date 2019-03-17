<template>
    <section id="reel" class="container">
        <div class="row">
            <h1 class="display-4 mx-auto">Reel</h1>
        </div>
        <div class="row">
            <div class="col-12 top-feature">
                <div class="media-container">
                    <div class="iframe-container">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/8pl_TiyQq7s" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-lg-4 col-md-12 bottom-feature">
                <div class="media-container">
                    <div class="iframe-container">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/u7ZDIS_jUtE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                </div>
            </div>
            <div class="col-lg-4 col-md-12 bottom-feature">
                <div class="media-container">
                    <div class="iframe-container">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/GrKVgtflDjw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                </div>
            </div>
            <div class="col-lg-4 col-md-12 bottom-feature">
                <div class="media-container">
                    <div class="iframe-container">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/A_WSLUOhsms" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        name: "Reel"
    }
</script>

<style lang="scss" scoped>
    .media-container {
        padding: 1rem;
    }
</style>
