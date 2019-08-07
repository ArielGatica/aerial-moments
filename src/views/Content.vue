<template>
    <section>
        <v-parallax :src="img.contentParallax" height="380">
            <v-layout column align-center justify-center>
                <div class="headline white--text mb-4 text-center">
                    Nada fija tan intensamente un recuerdo como el deseo de olvidarlo 
                </div>
                <em>Michel de Montaigne</em>
            </v-layout>
        </v-parallax>
        <v-card height="30"></v-card>
    </section>
</template>

<script>
    export default {
        data(){
            return{
                img:{
                   contentParallax: require('../assets/static/forest.jpg')
                }
            }
        }
    }
</script>
