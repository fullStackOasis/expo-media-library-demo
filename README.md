# Demo using expo-media-library in bare React Native project Android only

Uses expo-media-library 15.2.3 and React Native 0.71.8 with React 18.2.0.

Follow the instructions here:

https://docs.expo.dev/versions/latest/sdk/media-library/

Only for Android!!

You cannot **just** add `expo-media-library` to use the library. You also need to add expo.

## Expo

Next, run:

`npx install-expo-modules@latest`

This adds the required expo modules to `package.json`: expo^48.0.0.

It changes `android/app/src/main/java/com/expomedialibrarydemo/MainApplication.java` and `android/app/src/main/java/com/expomedialibrarydemo/MainActivity.java`, updates `build.gradle`, `settings.gradle`, and some ios files (who cares about ios? lol).

## Run the Demo

Now you can run the demo.

Press the blue button under the header that reads "OPEN MEDIA LIBRARY". Tap outside the system alert that opens (do not accept media permissions). A new `Alert` dialog opens. You should be able to tap the OK button. Once the dialog is gone, you should be able to scroll up and down as before.