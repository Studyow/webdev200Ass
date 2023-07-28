<!-- <template>
      

    <v-img
        :src="require('~/assets/hero/hero-desktop.jpg')"
        height="100%"
        class="bg-grey-lighten-2"
    ></v-img>

</template> -->

<template>
    <v-carousel hide-delimiters>
      <v-carousel-item
      class=""
        v-for="(item,i) in items"
        :key="i"
        :src="item.src"
        cover
      >
        <div class="">
        <v-banner
            color="pink-darken-1"
            icon="mdi-account-box"
            lines="two"
            class="align-end d-flex align-self-end"
            style="background-color: #ffffff70; bottom: -115px;"
        >
            <template v-slot:prepend>
            <v-avatar></v-avatar>
            </template>

            <h2>THIS SEASON'S BIGGEST DROP OF NEW GEAR</h2>
            <v-banner-text>
           get your hands on our latest and greatest gear and technology all built to make you better.
            </v-banner-text>

            <v-banner-actions class="d-flex justify-end">
            <v-btn color="info">Shop New Arrivals</v-btn>
            </v-banner-actions>
        </v-banner>
        </div>
    </v-carousel-item>
    </v-carousel>
  </template>

<script>
export default {
  data () {
    return {
      items: [
        {
          src: require('~/assets/hero/hero-desktop.jpg'),
        },
        {
          src: require('~/assets/hero/hero-desktop.jpg'),
        },
        {
          src: require('~/assets/hero/hero-desktop.jpg'),
        },
        {
          src: require('~/assets/hero/hero-desktop.jpg'),
        },
      ],
    }
  },
}
</script>