<template>
<v-app>
    <v-row>
        <v-col cols="12" sm="4">
            <v-hover v-slot:default="{ hover }">
                <v-card class="mx-auto" color="white lighten-4" max-width="600">
                    <v-img :aspect-ratio="16/9" src="https://cdn.vuetifyjs.com/images/cards/kitchen.png">
                        <v-expand-transition>
                            <div v-if="hover" class="d-flex transition-fast-in-fast-out black v-card--reveal display-3 white--text" style="height: 100%;">

                                <p style="position: absolute">Twoin Digitals</p>
                                <v-tooltip v-model="show" bottom>
                                    <template v-slot:activator="{ on }">
                                        <v-btn icon v-on="on" style="margin-top: 70px" href="http://twoindigital.com/"  target="_blank">
                                            <v-icon color="white lighten-1">visibility</v-icon>
                                        </v-btn>
                                    </template>
                                    <span>Go to site</span>
                                </v-tooltip>
                            </div>
                        </v-expand-transition>
                    </v-img>
                </v-card>
            </v-hover>
        </v-col>
        <v-col cols="12" sm="4">
            <v-hover v-slot:default="{ hover }">
                <v-card class="mx-auto" color="grey lighten-4" max-width="600">
                    <v-img :aspect-ratio="16/9" src="https://cdn.vuetifyjs.com/images/cards/kitchen.png">
                        <v-expand-transition>
                            <div v-if="hover" class="d-flex transition-fast-in-fast-out black darken-2 v-card--reveal display-3 white--text" style="height: 100%;">
                                <p style="position: absolute">Hillsdata Technologies</p>
                                <v-tooltip v-model="show" bottom>
                                    <template v-slot:activator="{ on }">
                                        <v-btn icon v-on="on" style="margin-top: 70px" href="https://hillsdatatechnologies.co.ke"  target="_blank">
                                            <v-icon color="white lighten-1">visibility</v-icon>
                                        </v-btn>
                                    </template>
                                    <span>Go to site</span>
                                </v-tooltip>
                            </div>
                        </v-expand-transition>
                    </v-img>
                </v-card>
            </v-hover>
        </v-col>
        <v-col cols="12" sm="4">
            <v-hover v-slot:default="{ hover }">
                <v-card class="mx-auto" color="grey lighten-4" max-width="600">
                    <v-img :aspect-ratio="16/9" src="https://nyumbanimart.co.ke/wp-content/uploads/2020/06/rsz_1rsz_2rsz_nyumbanimatt.png">
                        <v-expand-transition>
                            <div v-if="hover" class="d-flex transition-fast-in-fast-out black darken-2 v-card--reveal display-3 white--text" style="height: 100%;">
                                <p style="position: absolute">Nyumbani Mart</p>
                                <v-tooltip v-model="show" bottom>
                                    <template v-slot:activator="{ on }">
                                        <v-btn icon v-on="on" style="margin-top: 70px" href="https://nyumbanimart.co.ke/"  target="_blank">
                                            <v-icon color="white lighten-1">visibility</v-icon>
                                        </v-btn>
                                    </template>
                                    <span>Go to site</span>
                                </v-tooltip>
                            </div>
                        </v-expand-transition>
                    </v-img>
                </v-card>
            </v-hover>
        </v-col>
    </v-row>
</v-app>
</template>

<script>
export default {
    data() {
        return {
            show: false,
        }
    },
}
</script>

<style>
.v-card--reveal {
    align-items: center;
    bottom: 0;
    justify-content: center;
    opacity: .5;
    position: absolute;
    width: 100%;
}

.v-application .d-flex {
    font-size: 32px !important;
}
</style>
