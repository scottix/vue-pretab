<template>
  <ion-page>
    <ion-content>
      <ion-item router-link="/tabs/tab1">
        <ion-label>Click Me to Navigate</ion-label>
      </ion-item>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonContent, IonLabel, IonPage, IonItem } from '@ionic/vue';

export default {
  name: 'PreTab',
  components: {
    IonContent,
    IonPage,
    IonItem,
    IonLabel
  },
}
</script>
