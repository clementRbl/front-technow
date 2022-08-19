<template>
  <q-layout view="lHh Lpr lFf">
    <q-header style="background-color: #a32cdf">
      <q-toolbar class="row justify-center">
        <div class="text-h6 text-white text-uppercase font-harmony">
          Technow
        </div>
      </q-toolbar>
    </q-header>

    <q-page-container class="background">
      <div class="row">
        <div class="col-12">
          <router-view class="font-harmony" />
        </div>
      </div>
    </q-page-container>
  </q-layout>
</template>

<script setup lang="ts">
import { ref } from "vue";
</script>

<style lang="scss">
.background {
  background: linear-gradient(#a32cdf, #106ad2);
}
</style>
