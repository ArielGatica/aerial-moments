<template>
    <section>
        <v-layout
            column
            wrap
            class="my-12"
            align-center>
            
            <v-flex xs12 sm4 class="my-4">
                <div class="text-center">
                    <h2 class="headline">About Me?</h2>
                    <span class="subheading">
                        My focus is to make content
                    </span>
                </div>
            </v-flex>

            <v-flex xs12>
                <v-container grid-list-xl>
                    <v-layout row wrap align-center>
                        <v-flex xs12 md6>
                            <v-card flat class="transparent">
                                <v-card-text class="text-center">
                                    <v-icon size="65" color="lime darken-4">videocam</v-icon>
                                </v-card-text>
                                <v-card-title primary-title class="layout justify-center">
                                    <div class="headline text-center">Drone Video</div>
                                </v-card-title>
                                <v-card-text class="black--text">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                                    Nostrum repellat quibusdam consequatur molestias culpa ipsum, 
                                    repudiandae pariatur rerum asperiores reprehenderit laboriosam tempore hic. 
                                    Nisi, dolore ratione repellendus quo architecto ad.
                                </v-card-text>
                            </v-card>
                        </v-flex>
                        <v-flex xs12 md6>
                            <v-card flat class="transparent">
                                <v-card-text class="text-center">
                                    <v-icon size="65" color="lime darken-4">camera_enhance</v-icon>
                                </v-card-text>
                                <v-card-title primary-title class="layout justify-center">
                                    <div class="headline">Drone Picture</div>
                                </v-card-title>
                                <v-card-text class="black--text">
                                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. 
                                    Dignissimos voluptas, at voluptatum quia sapiente repellat error iure eveniet, 
                                    ipsa qui iusto libero mollitia, cum praesentium esse eos vel rem et?
                                </v-card-text>
                            </v-card>
                        </v-flex>
                    </v-layout>
                </v-container>
            </v-flex>
        </v-layout>
    </section>
</template>
