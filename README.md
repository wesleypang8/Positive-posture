# Posture
This application's purpose is to alert the user when his posture is bad. It utilizes the Microsoft Cognitive Services' Emotion API and the device's webcam to periodically check if the user is too close to the camera. If he is, then that means he is leaning his head down, so the application sends a notification to the user telling him to fix his posture. When first running the application, the user must calibrate the camera to the user's face at the correct posture/ distance. The application will correctly choose the user even if there are multiple faces in the background. In addition, the application can also "read" the user's emotions. If it seems that the user is angry or sad, then the application will send a notification with a joke in it.

An API key is required to use this application. https://www.microsoft.com/cognitive-services/en-us/emotion-api
