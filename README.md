This Article is created by Casper Gross Larsen and Jens Egeberg Rasmussen. By reading this article you will learn about localization and the use of this in our own little school project.

**Article 2 – Localization**



![](https://github.com/J-Egeberg/BallBoiV5/blob/master/localization.png)


It is getting hard to find a country that doesn't use android. Android is found in a thousand of different platforms in every corner of the world. Because of the extreme need and use of android devices, one might assume that it would be a good idea to implement multiple languages so it would be more enjoyable and usable for multiple clients.

To ensure, that the application, that you are making, reaches the most audience, you will want to enable localization.

**What is Localization?**

Localization handles all your media including, audio, text, currency, numbers, and converts it to the native language, that you are currently residing in. Localization is an extremely important part of modern app design. It is crucial for every app today that is supports localization.

Localization enables the apps within the mobile device to realize which country it is in via the settings within your phone. So if you switch your language within your phone from English to Danish, localization would take all the apps "Resources" and "translate" the overall language in the app.

Localization works the way that the programmer has a lot of resources that covers all the info and data within the app.
The programmer "hard codes" info into each of these resources and translates them himself into whatever languages he would like to add to his app. The was localization swaps between them is by naming the file folders correspondingly to the country code of whatever language he is writing in. For example, this could be done with pictures as well. So if you make a Danish folder you could implement a danish flag, and if you had an Eng folder you could implement an English flag.

These resources are the main topic in localization.

Resources are text strings, layouts, sounds, graphics, and any other static data that your Android app needs. 
An app can include multiple sets of resources, each customized for a different device configuration. 
When a user runs the app, Android automatically selects and loads the resources that best match the device.

When you write your app, you create default and alternative resources for your app to use. 
When users run your app, the Android system selects which resources to load, based upon the device's locale. 
To create resources, you place files within specially named subdirectories of the project's res/ directory.

**Purpose**

It's very efficient to make use of localization, especially if u want your application to make it across,
the world. Every nation has a different language and by using localization in your android application, you
make sure, that the default language is being set correctly, depending on your current location. All you have to do, is to set the language, accordingly in your phones settings.

**Why use it in our app?**

In our application, we decided to make use of the localization. In our res folder in the project folder, we have
placed two flags. One is used for converting resources into danish and the other is the default english language. 
(The English flag is not yet implemented). 

![local](https://github.com/J-Egeberg/BallBoiV5/blob/master/local.png)



Although it is going to be a minor feature in our application, (We're only deploying it with native danish & english language) it has really been a useful feature. It's very beneficial and easens the user experience a lot. If we were to target specific countries around the globe, it would require a lot more work. We believe it is sufficient to deploy it in english & danish, since it targets the majority of the population around the globe.


