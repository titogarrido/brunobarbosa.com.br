<template>
  <v-app light>
    <v-app-bar height="100px" flat color="transparent">
      <img class="ml-5" src="/logo-horizontal.png" height="60" />
      <v-divider class="mx-4 hidden-md-and-down" vertical></v-divider>
      <v-container class="hidden-md-and-down">
        <v-row justify="space-around">
          <v-btn
            height="110"
            text
            color="#387f3f"
            class="title"
            light
            @click="$vuetify.goTo('#sobre', { offset: +100 })"
            >Sobre
          </v-btn>

          <v-btn
            height="110"
            text
            color="#387f3f"
            class="title"
            light
            @click="$vuetify.goTo('#procedimentos', { offset: +65 })"
            >Procedimentos
          </v-btn>

          <v-btn
            height="110"
            text
            color="#387f3f"
            class="title"
            light
            @click="$vuetify.goTo('#contato', { offset: +65 })"
            >Contato
          </v-btn>
        </v-row>
      </v-container>
      <v-spacer />
      <v-btn color="#387f3f" icon @click.stop="rightDrawer = !rightDrawer">
        <v-icon>mdi-menu</v-icon>
      </v-btn>
    </v-app-bar>
    <v-main class="mt-0 pt-0">
      <v-container id="home" class="pa-0 ma-0" fluid>
        <nuxt />
      </v-container>
    </v-main>
    <v-navigation-drawer v-model="rightDrawer" :right="right" temporary fixed>
      <v-list>
        <v-list-item exact>
          <v-list-item-action>
            <v-icon>mdi-apps</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title
              @click="$vuetify.goTo('#home', { offset: +100 })"
            >
              Home
            </v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <v-list-item exact>
          <v-list-item-action>
            <v-icon>mdi-account</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title
              @click="$vuetify.goTo('#sobre', { offset: +350 })"
            >
              Sobre
            </v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <v-list-item exact>
          <v-list-item-action>
            <v-icon>mdi-needle</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title
              @click="$vuetify.goTo('#procedimentos', { offset: +40 })"
            >
              Procedimentos
            </v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <v-list-item exact>
          <v-list-item-action>
            <v-icon>mdi-phone</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title
              @click="$vuetify.goTo('#contato', { offset: -60 })"
            >
              Contato
            </v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-footer class="grey darken-3 white--text">
      <p>Copyright Bruno Barbosa&copy; 2020</p>
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
        }
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
