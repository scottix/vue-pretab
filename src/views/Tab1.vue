<template>
  <ion-page>
    <my-menu2 />
    <ion-header>
      <ion-toolbar>
        <ion-buttons>
          <ion-back-button default-href="/pretab"></ion-back-button>
          <ion-menu-button></ion-menu-button>
        </ion-buttons>
        <ion-title>Tab1</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content id="main2" :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 1</ion-title>
        </ion-toolbar>
      </ion-header>
      <ExploreContainer name="Tab 1 page" />
    </ion-content>
  </ion-page>
</template>

<script>
import MyMenu2 from '@/components/MyMenu2.vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonButtons, IonBackButton } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';

export default  {
  name: 'Tab1',
  components: { MyMenu2, ExploreContainer, IonHeader, IonToolbar, IonTitle, IonContent, IonPage, IonButtons, IonBackButton }
}
</script>
