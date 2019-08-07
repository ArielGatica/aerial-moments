<template>
    <div>
        <section>
            <v-parallax height="600" :src="img.homeParallax">
                <v-layout
                    column
                    align-center
                    justify-center
                    class="white--text">
                    <h1 class="white--text mb-2 display-1 text-center">From The Sky The View Is Better</h1>
                    <div class="subheading mb-4 text-center">By Ariel Gatica</div>
                </v-layout>
            </v-parallax>
        </section>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                img:{
                    homeParallax: require('../assets/static/sunset.jpg')
                }
            }
        }
    }
</script>
