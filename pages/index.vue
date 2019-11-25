<template>
  <v-app>
    <!--<v-carousel hide-delimiters>
      <v-carousel-item
        v-for="(item,i) in items"
        :key="i"
        :src="item.src"
      >
      </v-carousel-item>
    </v-carousel>-->
    <div class="hero_container">
      <v-img
        src="/1920x1080.png"
        aspect-ratio="1"
        max-height="500"
      ></v-img>
      <div class="hero_content pa-0">
        <v-container>
          <v-row class="ma-0">
            <v-col class="pb-12"
              cols="12"
            >
              <p class="hero_title text-left display-2 mb-3 font-weight-bold">Lorem ipsum</p>
              <p class="hero_subtext text-left subtitle-1 mb-6 font-weight-bold">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
              <v-btn rounded x-large depressed color="primary">Lorem Ipsum</v-btn>
            </v-col>
          </v-row>
        </v-container>
      </div>
    </div>

    <v-container class="pt-9 pb-9">
      <v-row>
        <v-col
          cols="12"
        >
          <p class="text-center display-1 pa-0">Lorem Ipsum</p>
          <p class="text-center pa-3 ma-0 body">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam tincidunt elit lorem, in posuere nisi ullamcorper at. Ut tortor diam, sagittis et lacus et, ultrices placerat enim. Suspendisse quis feugiat est. Nullam nec euismod purus, in accumsan felis. Maecenas in suscipit massa, sit amet facilisis lectus. Aliquam aliquet tellus sed tortor vestibulum volutpat. Quisque placerat tincidunt felis eget pellentesque.</p>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: '/1920x1080.png',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
          },
        ],
      }
    },
  }
</script>
