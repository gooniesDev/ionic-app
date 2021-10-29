<template>
  <ion-app>
    <ion-router-outlet />
  </ion-app>
</template>

<script>
import { IonApp, IonRouterOutlet } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'App',
  components: {
    IonApp,
    IonRouterOutlet
  }
});
/*
data(){
  return {
    fcm: new FCM();
  }
}

PushNotifications.requestPermission().then(result => {
      alert("result " + JSON.stringify(result));
    });
PushNotifications.addListener("registrationError", (error) => {
          console.log(`error on register ${JSON.stringify(error)}`);
        }),
        // Add tification received
          PushNotifications.addListener(
            "pushNotificationReceived",
            (notification) => {
              console.log(`notification ${JSON.stringify(notification)}`);
            }
          ),
          // Add Action performed
          PushNotifications.addListener(
            "pushNotificationActionPerformed",
            async (notification) => {
                alert("notification " + notification)
              console.log("notification succeeded");
            }
          ),
          // Initialize the registration with FCM Token
          PushNotifications.register();
        const fcmToken = this.fcm.getToken();
       alert(JSON.stringify(fcmToken));
        console.log("token:" + JSON.stringify(fcmToken));
  },
*/
</script>
