<template>
    <div class="page fill-height">
        <div class="landing">
            <v-parallax dark src="https://wallpaperaccess.com/full/1665315.jpg" height="900">
                <v-row align="center" justify="center" class="ma-0 ">
                    <v-col class="text-left description fill-height d-flex justify-center align-center px-14">
                        <div class="px-7">
                            <h1 class="mb-5 ">
                                Shelby GT500
                            </h1>
                            <p>
                                Pairing a 5.2L supercharged V8 with a dual-clutch TREMEC® 7-speed transmission, the 2021 Ford® Mustang Shelby GT500 delivers tire-smoking performance.
                            </p>
                            <v-btn @click="$vuetify.goTo('#about-section')" large class="rounded-0 mt-5 primary">Learn More</v-btn>
                        </div>
                    </v-col>
                    <v-col class="px-14 fill-height">
                        <v-row align="end" justify="end" class="fill-height">
                            <v-card class="ma-3" max-height="150" max-width="300">
                                <v-img max-height="150" max-width="300" class="d-flex justify-center align-center text-center" src="https://wallpapercave.com/wp/wp6831171.jpg">
                                    <v-btn large icon class="white">
                                        <v-icon>
                                            mdi-play
                                        </v-icon>
                                    </v-btn>
                                </v-img>
                            </v-card>
                            <v-card class="ma-3" max-height="350" max-width="250">
                                <v-img max-height="350" max-width="250" class="d-flex justify-center align-center text-center" src="https://i.pinimg.com/originals/0e/ef/35/0eef35140390be06f6db801718f5d126.jpg">
                                    <v-btn large icon class="white">
                                        <v-icon>
                                            mdi-play
                                        </v-icon>
                                    </v-btn>
                                </v-img>
                            </v-card>
                        </v-row>
                    </v-col>
                </v-row>
            </v-parallax>
        </div>
        <div class="whitespace"></div>
        <div class="about" id="about-section">
            <v-row>
                <v-col class="px-10">
                    <v-carousel hide-delimiters height="500">
                        <v-carousel-item v-for="(item,i) in showcase_imgs" :key="i" :src="item"></v-carousel-item>
                    </v-carousel>
                    <v-card class="mt-5 elevation-1 rounded-0">

                        <v-row class="pa-6">
                            <v-col class="text-center">
                                <v-card-subtitle>Horsepower</v-card-subtitle>
                                <div class="d-flex flex-row align-end justify-center">
                                    <h1>720 </h1><span>HP</span>
                                </div>
                            </v-col>
                            <v-divider vertical></v-divider>
                            <v-col class="text-center">
                                <v-card-subtitle>Torque</v-card-subtitle>
                                <div class="d-flex flex-row align-end justify-center">
                                    <h1>840 </h1><span>lb-ft</span>
                                </div>
                            </v-col>
                            <v-divider vertical></v-divider>

                            <v-col class="text-center">
                                <v-card-subtitle>0-60</v-card-subtitle>
                                <div class="d-flex flex-row align-end justify-center">
                                    <h1>3.8 </h1><span>sec</span>
                                </div>
                            </v-col>

                        </v-row>
                    </v-card>
                </v-col>

                <v-col>
                    <v-row class="fill-height" align="center" justify="center">
                        <v-col>
                            <div>
                                <h1 class="mb-5">
                                    2021 Mustang Shelby® GT500®
                                </h1>
                                <p style="width:80%" class="mb-5">
                                    GT500 the american muscle icon is back in 2021 with new 5.2L supercharged V8 with a dual-clutch TREMEC® 7-speed transmission, the 2021 Ford® Mustang Shelby GT500 delivers tire-smoking performance.
                                </p>
                                <v-btn large class="rounded-0 mr-3" color="primary">Build</v-btn>
                                <v-btn large class="rounded-0" outlined>View local inventory</v-btn>
                            </div>
                        </v-col>
                    </v-row>
                </v-col>
            </v-row>

        </div>
        <div class="whitespace"></div>
        <div class="features">
            <v-row>

                <v-spacer></v-spacer>

                <v-card class="mx-5" max-width="400">
                    <v-img class="white--text align-end" height="300px" src="https://www.ford.com/cmslibs/content/dam/vdm_ford/live/en_us/ford/nameplate/mustang/2021/collections/equipments/3_2/2020_GT500-Int-from-pass-Major-DC_2_32.jpg/_jcr_content/renditions/cq5dam.web.768.768.jpeg">
                        <v-card-title>RECARO <sup>®</sup>
                            Leather-trimmed Sport Seats</v-card-title>
                    </v-img>
                    <v-card-text class="text--primary">
                        <p>Ebony RECARO<sup>®</sup> leather-trimmed sport seats are race-inspired and deliver excellent support and comfort, even when you’re experiencing high lateral Gs during cornering. Available on EcoBoost<sup>®</sup> Premium and GT Premium with green accent stitch. *</p>
                    </v-card-text>
                </v-card>
                <v-card class="mx-5" max-width="400">
                    <v-img class="white--text align-end" height="300px" src="https://www.ford.com/cmslibs/content/dam/vdm_ford/live/en_us/ford/nameplate/mustang/2021/collections/equipments/3_2/19_FRD_MST_42405_PK_32.jpg/_jcr_content/renditions/cq5dam.web.768.768.jpeg">
                        <v-card-title>RECARO <sup>®</sup>
                            Leather-trimmed Sport Seats</v-card-title>
                    </v-img>
                    <v-card-text class="text--primary">
                        <p>Ebony RECARO<sup>®</sup> leather-trimmed sport seats are race-inspired and deliver excellent support and comfort, even when you’re experiencing high lateral Gs during cornering. Available on EcoBoost<sup>®</sup> Premium and GT Premium with green accent stitch. *</p>
                    </v-card-text>
                </v-card>
                <v-card class="mx-5" max-width="400">
                    <v-img class="white--text align-end" height="300px" src="https://www.ford.com/cmslibs/content/dam/vdm_ford/live/en_us/ford/nameplate/mustang/2021/collections/equipments/3_2/20_GT500_3Q_Front_Passenger_BLUE_DC_1_32.jpg/_jcr_content/renditions/cq5dam.web.768.768.jpeg">
                        <v-card-title>
                            Shelby<sup>®</sup>
                            GT500<sup>®</sup>
                            Carbon Fiber Track Pack
                        </v-card-title>
                    </v-img>
                    <v-card-text class="text--primary">
                        <p>The Carbon-Fiber Track Pack includes:</p>
                        <ul>
                            <li>20-inch exposed carbon-fiber wheels</li>
                            <li>Michelin<sup>®</sup> Pilot Cup Sport 2 tires<br>
                                - Front - 305/30R20<br>
                                - Rear - 315/30R20</li>
                            <li>Rear seat delete</li>
                            <li>Exposed carbon-fiber instrument panel</li>
                            <li>Exposed carbon-fiber GT4 track wing</li>
                            <li>Adjustable strut top mounts*</li>
                            <li>RECARO<sup>®</sup> leather-trimmed seats</li>
                            <li>Splitter wickers</li>
                            <li>Wheel-locking kit</li>
                        </ul>
                    </v-card-text>
                </v-card>
                <v-spacer></v-spacer>

            </v-row>
        </div>
        <div class="whitespace"></div>
        <div class="video">
            <v-row class="fill-height" align="center" justify="center">

                <v-col class="video-text pa-14 fill-height white--text">
                    <v-row class="fill-height" align="center" justify="center">
                        <v-col>
                            <div>
                                <h1 class="mb-6">
                                    Want to know more?
                                    watch these great reviews
                                </h1>

                                <v-btn large class="rounded-0 mr-3" color="primary">Performance</v-btn>
                                <v-btn large class="rounded-0">Experience</v-btn>
                            </div>
                        </v-col>
                    </v-row>
                </v-col>

                <v-col>
                    <div class="video-container">
                        <iframe src="https://www.youtube.com/embed/wecVzPzf8R4?start=5 &autoplay=1&mute=1&loop=1&rel=0&showinfo=0&iv_load_policy=3" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                </v-col>
            </v-row>

        </div>
        <div class="whitespace"></div>

    </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
    components: {
        Logo,
        VuetifyLogo
    },
    data() {
        return {
            showcase_imgs: [
                'https://build.ford.com/dig/Ford/Mustang/2021/HD-TILE/Image%5B%7CFord%7CMustang%7C2021%7C1%7C1.%7C950A.P8S..HX..88B.PRE.LRS.SLB.RWD.99J.LTS.64H.SSR.SY3.L59.SED.574.WCC.51H.PDS.RES.19B.18F.AFP.DIS.ANT.457.583.LET.TBJ.44G.GT5.COU.89V.2021%20P8S%20FORD.%5D/EXT/1/vehicle.png',
                'https://build.ford.com/dig/Ford/Mustang/2021/HD-TILE/Image%5B%7CFord%7CMustang%7C2021%7C1%7C1.%7C950A.P8S..HX..88B.PRE.LRS.SLB.RWD.99J.LTS.64H.SSR.SY3.L59.SED.574.WCC.51H.PDS.RES.19B.18F.AFP.DIS.ANT.457.583.LET.TBJ.44G.GT5.COU.89V.2021%20P8S%20FORD.%5D/EXT/2/vehicle.png',
                'https://build.ford.com/dig/Ford/Mustang/2021/HD-TILE/Image%5B%7CFord%7CMustang%7C2021%7C1%7C1.%7C950A.P8S..HX..88B.PRE.LRS.SLB.RWD.99J.LTS.64H.SSR.SY3.L59.SED.574.WCC.51H.PDS.RES.19B.18F.AFP.DIS.ANT.457.583.LET.TBJ.44G.GT5.COU.89V.2021%20P8S%20FORD.%5D/EXT/3/vehicle.png',
                'https://build.ford.com/dig/Ford/Mustang/2021/HD-TILE/Image%5B%7CFord%7CMustang%7C2021%7C1%7C1.%7C950A.P8S..HX..88B.PRE.LRS.SLB.RWD.99J.LTS.64H.SSR.SY3.L59.SED.574.WCC.51H.PDS.RES.19B.18F.AFP.DIS.ANT.457.583.LET.TBJ.44G.GT5.COU.89V.2021%20P8S%20FORD.%5D/EXT/4/vehicle.png',
                'https://build.ford.com/dig/Ford/Mustang/2021/HD-TILE/Image%5B%7CFord%7CMustang%7C2021%7C1%7C1.%7C950A.P8S..HX..88B.PRE.LRS.SLB.RWD.99J.LTS.64H.SSR.SY3.L59.SED.574.WCC.51H.PDS.RES.19B.18F.AFP.DIS.ANT.457.583.LET.TBJ.44G.GT5.COU.89V.2021%20P8S%20FORD.%5D/EXT/5/vehicle.png',

            ],

        }
    }
}
</script>

<style>
.page .landing .description {
    background: rgba(0, 0, 0, 0.4);
}
.v-parallax__content {
    padding: 0 !important;
}
.whitespace {
    height: 20vh;
}
.video {
    height: 70vh;
    position: relative;
}
.video .video-text {
    background: rgba(0, 0, 0, 0.4);
    position: absolute;
    z-index: 1;
    height: 65vh;
    width: 100%;
}
.video .video-container {
    overflow: hidden;
    height: 65vh;
    position: relative;
    width: 100%;
}

iframe {
    display: grid;

    place-items: center;
    height: 100vh;
    width: 100%;
    pointer-events: none;
    transform: scale(1.2);
}
</style>
