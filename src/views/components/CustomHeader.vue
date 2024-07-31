<template>
  <ion-header :translucent="true">
    <ion-toolbar class="toolbar-padding">
      <div>
        <ion-title>mathWorkbook</ion-title>
        <p class="version-number">v.0.1</p>
      </div>
      <!-- <ion-toggle slot="end" :checked="true" :enable-on-off-labels="true"></ion-toggle> -->
    </ion-toolbar>
  </ion-header>
</template>

<script setup lang="ts">
import { IonHeader, IonToolbar, IonTitle } from "@ionic/vue";
</script>

<style scoped>
.toolbar-padding {
  margin-right: 1em;
}
.version-number {
  color: #555555;
  margin: 0.5em 1.3em;
}
</style>
