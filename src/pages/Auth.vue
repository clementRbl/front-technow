<template>
  <q-page class="row justify-center flex flex-center">
    <div class="col-10">
      <q-form class="q-gutter-md">
        <div class="text-body1 text-center text-white text-uppercase">
          Connectez vous
        </div>
        <q-input
          v-model="dataForm.email"
          label="Email"
          type="email"
          outlined
          clearable
          clear-icon="close"
        />
        <q-input
          v-model="dataForm.password"
          label="Mot de passe"
          type="password"
          outlined
          clearable
          clear-icon="close"
        />
        <div class="q-mt-lg row justify-around items-center">
          <q-btn color="white" text-color="primary" label="S'enregistrer" />
          <q-btn color="white" text-color="secondary" label="Se Connecter" />
        </div>
      </q-form>
    </div>
  </q-page>
</template>

<script setup lang="ts">
import { ref } from "vue";
const dataForm = ref({
  email: "",
  password: "",
});
</script>

<style lang="scss"></style>
