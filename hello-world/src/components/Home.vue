<template>
    <div>
        <Slider :images="[
                {url: '../fond2.jpg'},
                {url: 'https://picsum.photos/300/300/?image=41'}
                ]"/>

        <div class="container">
            <div class="row">
                <div class="col-12 mt-4 mb-4">
                    <h4 class="text-center">« Parce que le soin énergétique n’est pas un don mais un pouvoir présent en chacun de nous.»</h4>
                </div>
                <div class="col-9">
                    <h1>Bienvenue !</h1>
                    <p class="text-justify">Nous vous souhaitons la bienvenue à l’école de soins énergétiques. Nous
                        proposons de nombreuses formations en médecine douce afin de vous
                        accompagner dans le développement de vos capacités de soins énergétiques.
                        Vous souhaitez pratiquer dans le domaine privé ou avez une ambition
                        professionnelle nos formations vous accompagnerons dans votre projet et
                        mettons notre expérience à votre disposition pour y parvenir.</p>

                    <h1>Nos formations</h1>
                    <b-card-group deck>
                        <b-card body-class="p-0" img-src="https://picsum.photos/300/300/?image=41" img-alt="Image" overlay>
                            <b-card-text class="pl-1 pr-1">
                                This is a wider card with supporting text below as a natural lead-in to additional content.
                                This content is a little bit longer.
                            </b-card-text>
                        </b-card>
                        <b-card body-class="p-0" img-src="https://picsum.photos/300/300/?image=41" img-alt="Image" overlay>
                            <b-card-text class="pl-1 pr-1">
                                This is a wider card with supporting text below as a natural lead-in to additional content.
                                This content is a little bit longer.
                            </b-card-text>
                        </b-card>
                        <b-card body-class="p-0" img-src="https://picsum.photos/300/300/?image=41" img-alt="Image" overlay>
                            <b-card-text class="pl-1 pr-1">
                                This is a wider card with supporting text below as a natural lead-in to additional content.
                                This content is a little bit longer.
                            </b-card-text>
                        </b-card>
                    </b-card-group>

                    <p class="mt-2 mb-2">Nos stages sont ouverts à tous et se déroulent sur Estreux au cœur de la Grange aux Idées</p>

                    <h1>Qui sommes-nous ?</h1>
                    <p class="text-justify">Après de nombreuses années de pratique au sein de mon cabinet, il m’a
                        semblé évident de transmettre mes connaissances en magnétisme et
                        soins énergétiques. C’est pour cette raison que j’ai crée l’Ecole de Soins
                        Energétiques avec pour volonté d’accompagner les personnes souhaitant
                        découvrir leurs capacités à maitriser leurs énergies pour soigner les autres.</p>

                </div>
                <div class="col-3 mt-3">

                    <b-alert show variant="success"><h6>Formations aux soins</h6>
                        énergétiques niveau 1<br/>
                        Le 21 et 22 Mars 2021
                        <b-button variant="outline-success" class="mt-3">En savoir plus</b-button>
                    </b-alert>

                    <b-alert show variant="success"><h6>Formations aux soins</h6>
                        énergétiques niveau 1<br/>
                        Le 12 et 13 Avril 2021
                        <b-button variant="outline-success" class="mt-3">En savoir plus</b-button>
                    </b-alert>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import Slider from './Slider.vue'

    export default {
        name: 'Home',
        components: {
            Slider,
        }
    }
</script>

<style scoped>
    .alert {
        text-align: center;
    }

    .card-text{
        background: #5a6268c7;
        color: white;
        bottom: 0;
        position: absolute;
    }



</style>
