<script>
export default {
    name: 'Card',
    props: {
        img: String,
        title: String
    }
}
</script>

<!-- CREAZIONE DI UN COMPONENTE GENERICO. I DATI LI LASCIO IN ComicsList.vue -->
<!-- <template>
    <div class="card">
        <div>img</div>
        <h3>titolo</h3>
    </div>
</template> -->


<!-- CREAZIONE DI UN COMPONENTE GENERICO DOPO AVER STABILITO I PROPS -->

<template>
    <div class="card">
        <div><img :src="img" alt=""></div>
        <h3>{{ title }}</h3>
    </div>
</template>

<!-- PER POPOLARE QUESTI COMPONENTI BISOGNA ANDARE AL PADRE (IN QUESTO CASO ComicsList.vue) -->