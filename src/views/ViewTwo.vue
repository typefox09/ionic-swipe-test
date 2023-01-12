<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-buttons slot="start">
          <ion-back-button></ion-back-button>
        </ion-buttons>
        <ion-title>New Item</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content></ion-content>
  </ion-page>
</template>


<script>
import { IonBackButton, IonButtons, IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
export default {
    name: 'ViewTwo',
    components: {
      IonBackButton,
      IonButtons,
      IonContent,
      IonHeader,
      IonPage,
      IonTitle,
      IonToolbar,
    },
}
</script>