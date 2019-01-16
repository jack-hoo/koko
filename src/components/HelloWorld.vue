<template>
    <div>
        <v-card>
            <v-responsive :aspect-ratio="16/9">
                <v-card-text>
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                    This card will always be 16:9 (unless you put more stuff in it)
                </v-card-text>
            </v-responsive>
        </v-card>
    </div>
</template>

<script>
    export default {
        data: () => ({
            lorem: `Lorem ipsum dolor sit amet, mel at clita quando. Te sit oratio vituperatoribus, nam ad ipsum posidonium mediocritatem, explicari dissentiunt cu mea. Repudiare disputationi vim in, mollis iriure nec cu, alienum argumentum ius ad. Pri eu justo aeque torquatos.`
        }),
        methods:{

        },
        mounted() {
            console.log(this.$vuetify.breakpoint)
        }
    }
</script>

<style scoped lang="scss">
    .container {
        background-color: darkgrey;
    }

    .item {
        min-height: 50px;
        min-width: 80px;
        margin: 10px;
    }
</style>
