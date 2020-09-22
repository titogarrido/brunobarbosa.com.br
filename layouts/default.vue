<template>
  <v-app light>
    <v-app-bar height="100px" hide-on-scroll app flat color="transparent">
      <img class="ml-5" src="/logo-horizontal.png" height="60" />
      <v-spacer />
      <v-btn icon @click.stop="rightDrawer = !rightDrawer">
        <v-icon>mdi-menu</v-icon>
      </v-btn>
    </v-app-bar>
    <v-img height="600px" src="/banner10.png"></v-img>
    <v-main class="mt-0 pt-0">
        <nuxt />
        <v-container>

        </v-container>
    </v-main>
    <v-navigation-drawer v-model="rightDrawer" :right="right" temporary fixed>
      <v-list>
        <v-list-item
          v-for="(item, i) in items"
          :key="i"
          :to="item.to"
          router
          exact
        >
          <v-list-item-action>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title v-text="item.title" />
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-footer :absolute="!fixed" app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<style scoped>
element.style {
  background-position: top center;
}
</style>

<script>
export default {
  data() {
    return {
      slides: [
        {
          src: "/banner6.png"
        },
        //{
        //  src:
        //    "http://localhost/unsafe/trim/smart/192.168.1.120:3000/banner3.jpg"
        //}
      ],
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: "mdi-apps",
          title: "Home",
          to: "/"
        },
        {
          icon: "mdi-chart-bubble",
          title: "Sobre",
          to: "/inspire"
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: "Vuetify.js"
    };
  }
};
</script>
