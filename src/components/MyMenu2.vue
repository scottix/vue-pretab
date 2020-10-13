<template>
  <ion-menu side="start" menu-id="first2" content-id="main2">
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
    name: "MyMenu2",
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
