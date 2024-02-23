<template>
  <v-app>
    <v-main>
      <v-container>
        <v-card>
          <v-card-title class="bg-purple">
            <v-icon>mdi-list-box-outline</v-icon> Lista de Tarefas</v-card-title
          >
          <v-card-text>
            <v-form ref="form">
              <div class="d-flex justify-space-between mt-4">
                <v-text-field
                  label="Nova tarefa"
                  variant="outlined"
                  density="compact"
                  class="mr-4"
                >
                </v-text-field>
                <v-btn color="purple" prepend-icon="mdi-send"> Adicionar</v-btn>
              </div>
            </v-form>

            <v-list>
              <v-list-item>
                <template #prepend>
                  <v-list-item-action start>
                    <v-checkbox-btn></v-checkbox-btn>
                  </v-list-item-action>
                </template>
                <template #append>
                  <v-icon>mdi-pencil</v-icon>
                  <v-icon class="ml-2">mdi-delete</v-icon>
                </template>

                <v-list-item-title>Limpar a casa</v-list-item-title>
              </v-list-item>

              <v-list-item>
                <template #prepend>
                  <v-list-item-action start>
                    <v-checkbox-btn></v-checkbox-btn>
                  </v-list-item-action>
                </template>
                <template #append>
                  <v-icon>mdi-pencil</v-icon>
                  <v-icon class="ml-2">mdi-delete</v-icon>
                </template>

                <v-list-item-title
                  >Levar os cachorros para passear</v-list-item-title
                >
              </v-list-item>

              <v-list-item>
                <template #prepend>
                  <v-list-item-action start>
                    <v-checkbox-btn></v-checkbox-btn>
                  </v-list-item-action>
                </template>
                <template #append>
                  <v-icon>mdi-pencil</v-icon>
                  <v-icon class="ml-2">mdi-delete</v-icon>
                </template>

                <v-list-item-title
                  >Escrever artigo sobre Hardware</v-list-item-title
                >
              </v-list-item>
            </v-list>
          </v-card-text>
          <div class="bg-purple pt-4"></div>
        </v-card>
      </v-container>
    </v-main>
  </v-app>
</template>


<script >
//
</script>
