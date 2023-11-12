> Why do I have a folder named ".expo" in my project?

The ".expo" folder is created when an Expo project is started using "expo start" command.

> What do the files contain?

- "devices.json": contains information about devices that have recently opened this project. This is used to populate the "Development sessions" list in your development builds.
- "packager-info.json": contains port numbers and process PIDs that are used to serve the application to the mobile device/simulator.
- "settings.json": contains the server configuration that is used to serve the application manifest.

> Should I commit the ".expo" folder?

No, you should not share the ".expo" folder. It does not contain any information that is relevant for other developers working on the project, it is specific to your machine.

Upon project creation, the ".expo" folder is already added to your ".gitignore" file.

NOTES
2023 11 13:
Modified and added code to test, but not expo was found / Didn't run properly
===

PS C:\Users\calfa\Documents\GitHub\React-Native-App> npx expo start
┌───────────────────────────────────────────────────────────────────────────┐
│ │
│ The global expo-cli package has been deprecated. │
│ │
│ The new Expo CLI is now bundled in your project in the expo package. │
│ Learn more: https://blog.expo.dev/the-new-expo-cli-f4250d8e3421. │
│ │
│ To use the local CLI instead (recommended in SDK 46 and higher), run: │
│ › npx expo <command> │
│ │
└───────────────────────────────────────────────────────────────────────────┘
Starting project at C:\Users\calfa\Documents\GitHub\React-Native-App
Unable to find expo in this project - have you run yarn / npm install yet?
PS C:\Users\calfa\Documents\GitHub\React-Native-App>
===
