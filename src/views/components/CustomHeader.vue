<template>
    <ion-header :translucent="true">
        <ion-toolbar class="toolbar-padding">
            <ion-title>mathWorkbook</ion-title>
            <!-- <ion-toggle slot="end" :checked="true" :enable-on-off-labels="true"></ion-toggle> -->
        </ion-toolbar>
    </ion-header>
</template>

<script setup lang="ts">
import { IonHeader, IonToolbar, IonTitle } from '@ionic/vue';
</script>

<style scoped>
    .toolbar-padding {
        margin-right: 1em;
    }
</style>