<template>
    <v-footer
        color="lime darken-4"
        padless>
        <v-layout
            justify-center
            wrap>
            <v-btn
                v-for="icon in icons"
                :key="icon"
                color="white"
                text
                rounded
                class="my-2">
                <v-icon size="24px">{{ icon }}</v-icon>
            </v-btn>
            <v-flex
                lime darken-4
                py-4
                text-center
                white--text
                xs12>
                {{ new Date().getFullYear() }} — <strong>Aerial Moments</strong>
            </v-flex>
        </v-layout>
    </v-footer>
</template>

<script>
    export default {
        data(){
            return{
                icons: [
                    'home',
                    'mail',
                    'event',
                    'delete'
                ]
            }
        }
    }
</script>
