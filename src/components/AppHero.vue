<script>
export default {
  name: 'AppHero',
  data() {
    return {
        imgName: 'img01.png',
    };
  },

  methods: {
    getImgUrl(img) {
        return new URL(`../assets/${img}`, import.meta.url).href;
    },
  },
}
</script>

<template>
    <div class="jumbotron">
        <div class="container">
            <div class="left">
                <h2>Jumbotron</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates, eveniet. Reprehenderit, magni rerum.
                    Fuga, itaque? Aspernatur, ad doloribus quod eveniet quae at voluptatem omnis, non officia libero
                    corrupti similique nostrum?</p>
                <img src="../assets/img01.png" alt="" />
            </div>
        </div>
    </div>
</template>

<style>
</style>