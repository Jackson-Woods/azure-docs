

1. Sign in to the [Firebase console](https://firebase.google.com/console/). Create a new Firebase project if you don't already have one.
2. After your project is created, click **Add Firebase to your Android app** and follow the instructions provided.

    ![](./media/notification-hubs-enable-firebase-cloud-messaging/notification-hubs-add-firebase-to-android-app.png)
3. In the Firebase console, click the cog for your project and then click **Project Settings**.

    ![](./media/notification-hubs-enable-firebase-cloud-messaging/notification-hubs-firebase-console-project-settings.png)
4. Click the **General** tab in your project settings, and then download the **google-services.json** file that contains the Server API key and Client ID.
5. Click the **Cloud Messaging** tab in your project settings, and copy the value of the **Legacy server key**. This value will be used to configure the notification hub access policy.
