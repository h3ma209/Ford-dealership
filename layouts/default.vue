<template>
    <v-app dark>
        
        <v-app-bar   app>
            <v-img class="mx-2" src="https://www.vhv.rs/dpng/d/483-4838435_shelby-mustang-logo-hd-png-information-shelby-cobra.png" max-height="40" max-width="40" contain></v-img>

            <v-toolbar-title v-text="title" />
            <v-spacer />

        </v-app-bar>
        <v-main>
            <v-container class="ma-0 pa-0" fluid>
                <nuxt />
            </v-container>
        </v-main>

        <v-footer app>
            <span>&copy; {{ new Date().getFullYear() }}</span>
        </v-footer>
    </v-app>
</template>

<script>
export default {
    data() {
        return {
            items: [
                {
                    icon: 'mdi-apps',
                    title: 'Welcome',
                    to: '/'
                },
                {
                    icon: 'mdi-chart-bubble',
                    title: 'Inspire',
                    to: '/inspire'
                }
            ],
            right: true,
            title: 'S H E L B Y'
        }
    }
}
</script>
