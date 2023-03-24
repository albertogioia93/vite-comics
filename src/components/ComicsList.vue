<script>
export default {
    nome: 'ComicsList'
}
</script>


<template>
    <section>
        <div class="container">
            <div class="fumetti">
                <div class="fumetto">FUMETTO</div>
                <div class="fumetto">FUMETTO</div>
                <div class="fumetto">FUMETTO</div>
                <div class="fumetto">FUMETTO</div>
                <div class="fumetto">FUMETTO</div>
                <div class="fumetto">FUMETTO</div>
                <div class="fumetto">FUMETTO</div>
                <div class="fumetto">FUMETTO</div>
                <div class="fumetto">FUMETTO</div>
                <div class="fumetto">FUMETTO</div>
                <div class="fumetto">FUMETTO</div>
                <div class="fumetto">FUMETTO</div>
            </div>
        </div>
    </section>
</template>


<style lang="scss" scoped>
section {
    background-color: #1c1c1c;
    // height: 500px;
    padding: 50px;
}

.fumetti {
    display: flex;
    flex-wrap: wrap;

    .fumetto {
        flex-basis: calc(100% / 6);
        border: 1px solid white;
        height: 230px;
    }
}
</style>