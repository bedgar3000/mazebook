<template>
    <div class="home">
        <div class="container">
            <div class="row">
                <div class="col">
                    <div class="img-container">
                        <img class="mx-auto" alt="Vue logo" src="../assets/img/wordmark.svg">
                        <h2 class="text-center text-lg-start">Conéctate con amigos y el resto del mundo usando mazebook.</h2>
                    </div>
                </div>
                <div class="col">
                    <div class="card" style="width: 18rem;">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                            <a href="#" class="btn btn-primary">Go somewhere</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'HomeView',
        components: { }
    }
</script>

<style scoped>
    .home {
        max-width: 895px;
        margin: auto;
    }
</style>