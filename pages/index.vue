<template>
  <div>
    <v-img height="600px" src="/banner-rascunho2.jpeg">
      <v-row style="height: 100%" align="center">
        <v-col cols="12" md="2"></v-col>
        <v-col class="text-center" cols="12" md="4">
          <v-img
            lazy-src="/logo-branco-horizontal.png"
            src="/logo-branco-horizontal.png"
          ></v-img>
        </v-col>
      </v-row>
    </v-img>

    <v-container fluid>
      <v-row class="mx-5 my-5" align="center" justify="center">
        <v-col class="text-center" cols="12" md="4">
          <v-avatar size="300">
            <v-img src="/avatar7.jpg"></v-img>
          </v-avatar>
        </v-col>
        <v-col cols="12" md="8">
          <div id="sobre" class="text-h5 text-left font-weight-medium mb-5">
            Dr. Bruno Barbosa
          </div>
          <div class="text-h5  text-left font-weight-light">
            Médico clínico. Pratica uma medicina centrada no paciente e em suas
            necessidades, baseado nas melhores evidências científicas atuais. O
            objetivo é manter a harmonia física e mental, tendo como pilares o
            bem estar, a qualidade de vida e o emagrecimento saudável.
          </div>
        </v-col>
      </v-row>
    </v-container>
    <v-container
      fluid
      style="background-image: url('/consultorio1.jpeg'); opacity: 0.8;"
    >
      <v-row align="center" justify="center" class="mx-5">
        <v-col cols="12" md="12">
          <div id="procedimentos" class="text-center text-h4 mt-5">Procedimentos</div>
        </v-col>
        <v-container class="white my-5 mx-5">
          <v-row align="center" justify="center">
            <v-col class="text-center" cols="12" md="4">
              <v-avatar class="ma-3" size="200">
                <v-img src="/dna5.gif"></v-img>
              </v-avatar>
            </v-col>
            <v-col cols="12" md="8">
              <div class="mr-5">
                <h2>Teste Genético</h2>
                A revolução genômica tem trazido cada vez mais acessível ao
                paciente uma compreensão de si mesmos através dos resultados dos
                testes genéticos, promovendo assim mais saúde, conhecimento e
                bem-estar.
              </div>
            </v-col>
          </v-row>
        </v-container>
        <v-container class="white my-5 mx-5">
          <v-row align="center" justify="center">
            <v-col cols="12" md="8">
              <div class="ml-5">
                <h2>Protocolos Personalizados</h2>
                A revolução genômica tem trazido cada vez mais acessível ao
                paciente uma compreensão de si mesmos através dos resultados dos
                testes genéticos, promovendo assim mais saúde, conhecimento e
                bem-estar.
              </div>
            </v-col>
            <v-col class="text-center" cols="12" md="4">
              <v-avatar class="ma-3" size="200">
                <v-img src="/medicamentos4.jpg"></v-img>
              </v-avatar>
            </v-col>
          </v-row>
        </v-container>
      </v-row>
    </v-container>
    <!--   <v-container fluid class="grey lighten-3">
      <v-row
        class="mx-5 my-5"
        align="center"
        justify="center"
      >
        <v-col class="text-center" cols="12" md="12">
          <span class="text-h2">Artigos</span>
        </v-col>
        <v-col cols="12" md="4">
          <v-card class="mx-auto" max-width="400">
            <v-img
              class="white--text align-end"
              height="200px"
              src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
            >
              <v-card-title>Top 10 Australian beaches</v-card-title>
            </v-img>

            <v-card-subtitle class="pb-0">
              Number 10
            </v-card-subtitle>

            <v-card-text class="text--primary">
              <div>Whitehaven Beach</div>

              <div>Whitsunday Island, Whitsunday Islands</div>
            </v-card-text>

            <v-card-actions>
              <v-btn color="orange" text>
                Compartilhe
              </v-btn>

              <v-btn color="orange" text>
                Leia Agora
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col cols="12" md="4">
          <v-card class="mx-auto" max-width="400">
            <v-img
              class="white--text align-end"
              height="200px"
              src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
            >
              <v-card-title>Top 10 Australian beaches</v-card-title>
            </v-img>

            <v-card-subtitle class="pb-0">
              Number 10
            </v-card-subtitle>

            <v-card-text class="text--primary">
              <div>Whitehaven Beach</div>

              <div>Whitsunday Island, Whitsunday Islands</div>
            </v-card-text>

            <v-card-actions>
              <v-btn color="orange" text>
                Compartilhe
              </v-btn>

              <v-btn color="orange" text>
                Leia Agora
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col cols="12" md="4">
          <v-card class="mx-auto" max-width="400">
            <v-img
              class="white--text align-end"
              height="200px"
              src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
            >
              <v-card-title>Top 10 Australian beaches</v-card-title>
            </v-img>

            <v-card-subtitle class="pb-0">
              Number 10
            </v-card-subtitle>

            <v-card-text class="text--primary">
              <div>Whitehaven Beach</div>

              <div>Whitsunday Island, Whitsunday Islands</div>
            </v-card-text>

            <v-card-actions>
              <v-btn color="orange" text>
                Compartilhe
              </v-btn>

              <v-btn color="orange" text>
                Leia Agora
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
    </v-container> -->
    <v-container id="contato" fluid class="grey">
      <v-row class="mt-5" align="center" justify="center">
        <v-col cols="12" md="10">
          <v-card light>
            <v-row>
              <v-col cols="12" md="6">
                <div class="ml-5 mt-5">
                  <p class="text-h5 text-uppercase">Telefones</p>
                  <p class="text-subtitle-1">(71) 3506-9937</p>
                  <p class="text-subtitle-1">(71) 99603-9927</p>
                  <v-btn target="_blank" href="https://api.whatsapp.com/send?phone=5571996039927&text=Ol%C3%A1%2C%20gostaria%20de%20agendar%20uma%20consulta%20com%20o%20Dr.%20Bruno%20Barbosa." class="mb-5" tile color="success">
                      <v-icon left>
                        mdi-whatsapp
                      </v-icon>
                      Agendar Consulta
                    </v-btn>
                  <p class="text-h5 text-uppercase">Email</p>
                  <p class="text-subtitle-1">contato@drbrunobarbosa.com.br</p>
                  <p class="text-h5 text-uppercase">Endereço</p>
                  <p class="text-subtitle-1">
                    Rua Arthur de Azevêdo Machado, 1459, Sala 2511, Edf.
                    Internacional Trade Center, Costa Azul, Salvador - BA, CEP:
                    41770-790
                  </p>
                </div>
              </v-col>
              <v-col cols="12" md="6">
                <v-card-title class="text-h5 text-center text-uppercase">Onde Estamos</v-card-title>
                <v-card-text class="text-center mt-5">
                  <iframe
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3887.7627680552223!2d-38.45083428482303!3d-12.987019590845755!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7161b0ed26c658b%3A0x9f5b7800c77eb974!2sInternacional%20Trade%20Center%20-%20ITC%20Salvador!5e0!3m2!1spt-BR!2sbr!4v1601671680658!5m2!1spt-BR!2sbr"
                    width="300"
                    height="300"
                    frameborder="0"
                    style="border:0;"
                    allowfullscreen=""
                    aria-hidden="false"
                    tabindex="0"
                  ></iframe>
                </v-card-text>
              </v-col>
            </v-row>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {};
  }
};
</script>
