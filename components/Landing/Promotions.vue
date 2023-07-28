<template>
    <v-container>
        <h4>Special Offers</h4> <br>

        <v-layout row wrap class="d-flex justify-center">

            <v-flex xs12 md4 lg4>
                <v-card class="ma-2">
                    <v-img
                    :src="require('~/assets/brand-background/Nike-2020-Forum_original 2.jpg')"
                    max-height="205"
                    class="bg-grey-lighten-2"
                    ></v-img>
                    <v-card-title class="text-h6">
                        <img 
                        :src="require('~/assets/brands/1200px-Adidas_Logo 1.png')"
                        width="80"
                        />
                        <h3 class="ma-2">Low as 60%</h3>
                        <div class="ma-2"><h6>coupon:</h6><h5>VXHOOYNO-2552</h5></div>
                    </v-card-title>
                </v-card>
            </v-flex>

            <v-flex xs12 md4 lg4>
                <v-card class="ma-2">
                    <v-img
                    :src="require('~/assets/brand-background/Nike-2020-Forum_original 1.jpg')"
                    max-height="205"
                    class="bg-grey-lighten-2"
                    ></v-img>
                    <v-card-title class="text-h6">
                        <img 
                        :src="require('~/assets/brands/nike_logo 1.png')"
                        width="100"
                        />
                        <h3 class="ma-2">Low as 30%</h3>
                        <div class="ma-2"><h6>coupon:</h6><h5>SDFGGTAS-2552</h5></div>
                    </v-card-title>
                </v-card>
            </v-flex>

            <v-flex xs12 md4 lg4>
                <v-card class="ma-2">
                    <v-img
                    :src="require('~/assets/brand-background/Nike-2020-Forum_original 3.jpg')"
                    max-height="205"
                    class="bg-grey-lighten-2"
                    ></v-img>
                    <v-card-title class="text-h6">
                        <img 
                        :src="require('~/assets/brands/1200px-Under_armour_logo 1-1.png')"
                        width="90"
                        />
                        <h3 class="ma-2">Low as 40%</h3>
                        <div class="ma-2"><h6>coupon:</h6><h5>HSFGDFHD-2552</h5></div>
                    </v-card-title>
                </v-card>
            </v-flex>

        </v-layout>

        

    </v-container>
  </template>