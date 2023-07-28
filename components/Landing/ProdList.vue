<template>
    <v-container class="bg-surface-variant">
        <h4>Top Trending</h4>
      <v-row no-gutters>
        <v-col
          v-for="n in 4"
          :key="n"
          cols="12"
          sm="3"
        >
          <v-sheet class="ma-2 pa-2">
            <v-card
                class="mx-auto"
                max-width="400"
            >
                <v-img
                class="align-end text-white"
                height="200"
                :src="require('~/assets/product-image/image-9.png')"
                cover
                >
                <v-card-title>Mens UA Tech Jacket</v-card-title>
                </v-img>

                <v-card-subtitle class="pt-4">
                Brooklyn 13
                </v-card-subtitle>

                <v-card-text>
                <div>Gray White Space Jacket, All the way to BROOKLYN</div>
                <h4>$29.99</h4>
                </v-card-text>

                <v-card-actions class="justify-center">
                <v-btn color="info">
                    Buy
                </v-btn>

                </v-card-actions>
            </v-card>
          </v-sheet>
        </v-col>
      </v-row>
    </v-container>
  </template>