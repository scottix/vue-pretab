<template>
  <ion-menu side="start" menu-id="first" content-id="main">
    <ion-header>
      <ion-toolbar>
        <ion-title>My Menu</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content>
      <ion-list>
        <ion-item to="/tabs/tab1">Tab1</ion-item>
      </ion-list>
    </ion-content>
  </ion-menu>
</template>

<script>
  import {
    IonHeader,
    IonContent,
    IonMenu,
    IonTitle,
    IonToolbar,
    IonList,
    IonItem
  } from '@ionic/vue';

  export default {
    name: "MyMenu",
    components: {
      IonHeader,
      IonContent,
      IonMenu,
      IonTitle,
      IonToolbar,
      IonList,
      IonItem
    }
  };
</script>
