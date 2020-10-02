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
          <div class="text-h5 text-left font-weight-medium mb-5">
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
          <div class="text-center text-md-h2 text-xs-h3">Procedimentos</div>
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
                        color="primary"
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
                  <p class="text-subtitle-1">(71) 3506-9937</p>
                  <p class="text-subtitle-1">(71) 99603-9927</p>
                  <p class="text-h5 text-uppercase">Email</p>
                  <p class="text-subtitle-1">contato@drbrunobarbosa.com.br</p>
                  <p class="text-h5 text-uppercase">Endereço</p>
                  <p class="text-subtitle-1">
                    Rua Arthur de Azevêdo Machado, 1459, Sala 2511, Edf. Internacional Trade Center, Costa Azul, Salvador - BA, CEP: 41770-790
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
