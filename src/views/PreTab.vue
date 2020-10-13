<template>
  <ion-page>
    <my-menu />
    <ion-header>
      <ion-toolbar>
        <ion-buttons slot="start">
          <ion-menu-button menu="first"></ion-menu-button>
        </ion-buttons>
        <ion-title class="ion-text-center">PreTab</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content id="main">
      <ion-item router-link="/tabs/tab1">
        <ion-label>Click Me to Navigate</ion-label>
      </ion-item>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import MyMenu from '@/components/MyMenu.vue';
import { IonPage, IonHeader, IonToolbar, IonButtons, IonMenuButton, IonContent, IonItem, IonLabel } from '@ionic/vue';

export default {
  name: 'PreTab',
  components: {
    MyMenu,
    IonPage,
    IonHeader,
    IonToolbar,
    IonButtons,
    IonMenuButton,
    IonContent,
    IonItem,
    IonLabel
  },
}
</script>
