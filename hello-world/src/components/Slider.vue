<template>
 <div>
     <b-carousel
             id="carouselMain"
             v-model="slide"
             :interval="4000"
             controls
             indicators
             background="#ababab"
             style="text-shadow: 1px 1px 2px #333;"
             @sliding-start="onSlideStart"
             @sliding-end="onSlideEnd"
     >
         <b-carousel-slide v-for="(img, idx) in images"
                           :img-src="img.url"
                           :key="idx"></b-carousel-slide>

     </b-carousel>
 </div>
</template>

<script>

    export default {
        name: 'Slider',
        props: {
            images: Array
        },
        data: () => {
            return {
                slide: 0,
                sliding: null
            }
        },
        methods: {
            onSlideStart() {
                this.sliding = true
            },
            onSlideEnd() {
                this.sliding = false
            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .carousel-item {
        max-height: 450px;
    }
</style>
