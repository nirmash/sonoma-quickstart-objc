# sonoma-quickstart-objc

iOS/Objective-C Todo List for Sonoma Bug Bash

1. Create an app in Sonoma
2. Link a subscription
3. Create a Table under Tables called "todoitem" with a string field called "text" and a boolean field called "complete"
4. Go to **Getting Started** and **Manage App**
5. Make a note of the App Secret.
6. Edit the file ZUMOAPPNAME/QSTodoService.m
    * Look for the string `ZUMOAPPURL`
    * Replace it with `https://mobile-{appsecret}.azurewebsites.net`
    * Replace {appsecret} with the App Secret you noted above (it's a GUID)


You should now be able to build and run the application in an iOS Simulator against your mobile backend in Sonoma.