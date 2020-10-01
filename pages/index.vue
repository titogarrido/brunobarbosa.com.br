<template>
  <div>
    <v-img height="600px" src="/banner-rascunho2.jpeg">
      <v-row
        style="background-color: black; opacity: 0.6; margin-left:-20px; margin-right:-20px; height: 100%"
        align="center"
      >
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
        <v-col cols="12" md="4">
          <v-img src="/avatar7.jpg"></v-img>
        </v-col>
        <v-col cols="12" md="8">
          <div class="text-h5  text-left font-weight-medium mb-5">
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
      style="background-image: url('/consultorio1.jpeg'); opacity: 0.6; height: 500px;"
    >
      <v-row align="center" justify="center" class="mx-5">
        <v-col class="text-center" cols="12" md="12">
          <span class="text-h2">Procedimentos</span>
        </v-col>
        <v-col cols="12" md="6">
          <v-card class="mx-5 mb-5">
            <div class="d-flex flex-no-wrap justify-space-between">
              <div>
                <v-card-title class="headline mt-5 mb-5"
                  >Teste Genético</v-card-title
                >

                <v-card-subtitle class="mb-5">
                  A revolução genômica tem trazido cada vez mais acessível ao
                  paciente uma compreensão de si mesmos através dos resultados
                  dos testes genéticos, promovendo assim mais saúde,
                  conhecimento e bem-estar.
                </v-card-subtitle>
              </div>

              <v-avatar class="ma-3" size="125" tile>
                <v-icon x-large>mdi-dna</v-icon>
              </v-avatar>
            </div>
          </v-card>
        </v-col>
        <v-col cols="12" md="6">
          <v-card class="mx-5 mb-5">
            <div class="d-flex flex-no-wrap justify-space-between">
              <div>
                <v-card-title class="headline mt-5 mb-5"
                  >Protocolos Personalizados</v-card-title
                >

                <v-card-subtitle class="mb-5">
                  A revolução genômica tem trazido cada vez mais acessível ao
                  paciente uma compreensão de si mesmos através dos resultados
                  dos testes genéticos, promovendo assim mais saúde,
                  conhecimento e bem-estar.
                </v-card-subtitle>
              </div>

              <v-avatar class="ma-3" size="125" tile>
                <v-icon x-large>mdi-playlist-check</v-icon>
              </v-avatar>
            </div>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
    <v-container fluid class="grey lighten-3">
      <v-row
        style="height: 500px;"
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
    </v-container>
    <v-container fluid class="black">
      <v-row class="mt-5" align="center" justify="center">
        <v-col cols="12" md="10">
          <v-card light>
            <v-row>
              <v-col cols="12" md="6">
                <div>
                  <v-card-title class="display-1">Fale Conosco</v-card-title>

                  <v-card-text>
                    <v-form ref="form" v-model="valid" lazy-validation>
                      <v-text-field label="Nome" required></v-text-field>

                      <v-text-field label="E-mail" required></v-text-field>

                      <v-text-field label="Telefone" required></v-text-field>

                      <v-textarea label="Mensagem" required> </v-textarea>

                      <v-btn
                        :disabled="!valid"
                        color="success"
                        class="mr-4"
                        @click="validate"
                      >
                        Enviar
                      </v-btn>
                    </v-form>
                  </v-card-text>
                </div>
              </v-col>

              <v-col class="grey" cols="12" md="6">
                <div class="ml-5 mt-5">
                <p class="text-h5 text-uppercase">Telefones</p>
                <p class="text-subtitle-1">71 9190-1146</p>
                <p class="text-subtitle-1">11 XXXX-1146</p>
                <p class="text-h5 text-uppercase">Email</p>
                <p class="text-subtitle-1">bruno@drbrunobarbosa.com.br</p>
                <p class="text-h5 text-uppercase">Endereços</p>
                <p class="text-subtitle-1">
                  Rua Borges Lagoa 1080, Sala 1210, Vila Clementino - São Paulo
                  - SP
                </p>
                <p class="text-subtitle-1">
                  Rua Borges Lagoa 1080, Sala 1210, Vila Clementino - São Paulo
                  - SP
                </p>
                </div>
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
