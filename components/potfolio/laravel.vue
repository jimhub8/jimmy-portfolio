<template>
<v-app>
    <v-row>
        <v-col cols="12" sm="4">
            <v-hover v-slot:default="{ hover }">
                <v-card class="mx-auto" color="grey lighten-4" max-width="600">
                    <v-img :aspect-ratio="16/9" src="/images/inventory.png">
                        <v-expand-transition>
                            <div v-if="hover" class="d-flex transition-fast-in-fast-out black darken-2 v-card--reveal display-3 white--text" style="height: 100%;">
                                <p style="position: absolute">MFT Fulfillment Centre</p>
                                <v-tooltip v-model="show" bottom>
                                    <template v-slot:activator="{ on }">
                                        <v-btn icon v-on="on" style="margin-top: 70px" href="http://warehouse.swapstore.co.ke" target="_blank">
                                            <v-icon color="white lighten-1">visibility</v-icon>
                                        </v-btn>
                                    </template>
                                    <span>See a demo</span>
                                </v-tooltip>
                            </div>
                        </v-expand-transition>
                    </v-img>
                </v-card>
            </v-hover>
        </v-col>
        <v-col cols="12" sm="4">
            <v-hover v-slot:default="{ hover }">
                <v-card class="mx-auto" color="white lighten-4" max-width="600">
                    <v-img :aspect-ratio="16/9" src="/images/courier.jpeg">
                        <v-expand-transition>
                            <div v-if="hover" class="d-flex transition-fast-in-fast-out black v-card--reveal display-3 white--text" style="height: 100%;">
                                <p style="position: absolute">Speedball Courier</p>
                                <v-tooltip v-model="show" bottom>
                                    <template v-slot:activator="{ on }">
                                        <v-btn icon v-on="on" style="margin-top: 70px">
                                            <v-icon color="white lighten-1">visibility</v-icon>
                                        </v-btn>
                                    </template>
                                    <span>Learn More</span>
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
                    <v-img :aspect-ratio="16/9" src="/images/insurance.jpeg">
                        <v-expand-transition>
                            <div v-if="hover" class="d-flex transition-fast-in-fast-out black darken-2 v-card--reveal display-3 white--text" style="height: 100%;">
                                <p style="position: absolute">Willo Insurance Agency</p>
                                <v-tooltip v-model="show" bottom>
                                    <template v-slot:activator="{ on }">
                                        <v-btn icon v-on="on" style="margin-top: 70px">
                                            <v-icon color="white lighten-1">visibility</v-icon>
                                        </v-btn>
                                    </template>
                                    <span>Learn More</span>
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
                    <v-img :aspect-ratio="16/9" src="/images/e-commerce.png">
                        <v-expand-transition>
                            <div v-if="hover" class="d-flex transition-fast-in-fast-out black darken-2 v-card--reveal display-3 white--text" style="height: 100%;">
                                <p style="position: absolute">Dellmat</p>
                                <v-tooltip v-model="show" bottom>
                                    <template v-slot:activator="{ on }">
                                        <v-btn icon v-on="on" style="margin-top: 70px"  href="https://dellmat.com"  target="_blank">
                                            <v-icon color="white lighten-1">visibility</v-icon>
                                        </v-btn>
                                    </template>
                                    <span>View Website</span>
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
                                <p style="position: absolute">Boxleo Website</p>
                                <v-tooltip v-model="show" bottom>
                                    <template v-slot:activator="{ on }">
                                        <v-btn icon v-on="on" style="margin-top: 70px" href="https://boxleo.co.ke" target="_blank">
                                            <v-icon color="white lighten-1">visibility</v-icon>
                                        </v-btn>
                                    </template>
                                    <span>View Website</span>
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
