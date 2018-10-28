# Native vs. Web vs. Hybrid Apps — What’s the Difference?

![logo](https://cdn-images-1.medium.com/max/1600/1*S94F7x6dGMspXPPbiLbw-A.jpeg)

In the mobile realm, you’ll hear often terms like **native app** or **web app**, or even **hybrid app**. What’s the difference?

***

## Native app

### What is a native app?

A **native app** is one built specifically for the platform it will serve. These apps might come pre-installed on your smartphone or tablet, or you can find them in the app store you use (e.g., GooglePlay or Apple’s App Store). Android and Apple (iOS) systems work differently, and a native app is built and coded specifically for the operating system on which you want it to work. The iPhone’s camera is a native app. So is Instagram, which operates within the app on your device — even though Instagram has versions on both platforms.

Native apps are developed specifically for one platform, and can take full advantage of all the device features — they can use the camera, the GPS, the accelerometer, the compass, the list of contacts, and so on. They can also incorporate gestures (either standard operating-system gestures or new, app-defined gestures). And native apps can use the device’s notification system and can work offline.


![native](https://qph.fs.quoracdn.net/main-qimg-0483bd3def66d829570bcc6e78e0ad87)

### How are Native apps built?

Native apps are applications written in languages that the platform they are being built for accepts. For example, Swift or Objective-C is used to write native iOS apps, Java is used to write native Android apps, and C# for the most part for Windows Phone apps.

### Pros of Native apps

* Native apps are very fast and responsive because they are built for that specific platform
* They have the best performance
* They are more interactive, intuitive and run much smoother in terms of user input and output
* Native allows developers to access the full feature set of their given platform with whatever performance optimizations the native system has
* Internet connection is not required, although it depends on the functionality
* Overall better user experience. To the user, the flow is more natural as they have specific UI standards for each platform

### Cons of Native apps

* The cost and time to build a native app are usually higher than the other options.
* Because a native app is only released for its own platform, you’ll have to build different versions.

***

## Web app

### What is a web app?

**Web apps** are not real applications; they are really websites that, in many ways, look and feel like native applications, but are not implemented as such. They are run by a browser and typically written in HTML5. Users first access them as they would access any web page: they navigate to a special URL and then have the option of “installing” them on their home screen by creating a bookmark to that page.

Web apps became really popular when HTML5 came around and people realized that they can obtain native-like functionality in the browser. Today, as more and more sites use HTML5, the distinction between web apps and regular web pages has become blurry.

![web](https://content-static.upwork.com/blog/uploads/sites/3/2015/05/05084031/MOB_native-vs-web-app-whats-the-diff-which-do-i-need_M.png)

### How are Web apps built?

The vast majority of Web Apps are built in **JavaScript**, **CSS**, and **HTML5**.
There are templates and frameworks like **React** and **Vue.js** that can be used to get a quick start.
As opposed to mobile apps, developing a web app can be **simple and quick**.

### Pros of Web apps

* Easy to build
* Easy to maintain
* An Inexpensive option
* Build one app for all platforms – iOS, Android, etc. as long as it can run a browser

### Cons of Web apps

* Needs a browser to run. Users have to take another step to type in the URL of the app which amounts to a poor user experience
* Much slower than native apps
* Web apps are less interactive and intuitive than native apps
* No icon on mobile desktop as you would if it was downloaded from the app stores
* Cannot leverage device utilities

***

## Hybrid App

### What is a hybrid app?

Hybrid apps work across platforms and behave like native apps. A hybrid app is essentially a combination of a native app and a web app. Users can install it on their device like a native app but it is actually a web app. These types of apps are built with Javascript, HTML, and CSS and run in Webview.

Hybrid app development can essentially do everything HTML5 does, except it also incorporates native app features. This is possible when you deploy a wrapper to act as a bridge between platforms to access the native features.

A hybrid app consists of two parts. The first is the back-end code built using languages such as HTML, CSS, and Javascript. The second is a native shell that is downloadable and loads the code using Webview.

![hybrid](https://www.impigertech.com/wp-content/uploads/2016/11/Hybrid-header-v2.png)

### Pros of Hybrid Apps

* Built on web technology HTML/ CSS/ Javascript so it’s much easier to build
* Cheaper than a native app
* One app for all platforms using technology like Cordova
* No browser needed as opposed to a web app
* Have access to the device’s internal APIs, can access storage, camera, etc.
* Faster to develop than native apps because you have a single code base

### Cons of Hybrid Apps

* Slower than native apps
* More expensive than standard web apps because you have to work with the wrapper. Essentially you’re dependent on a third party platform
* Less interactive than native apps
* Customization will take you away from the hybrid model in which you may as well go native

***

## What Type of App is Best For You?

In order to make the right choice, it’s important to understand the differences of each option and so you can head in the right direction. Native, mobile web, and hybrid applications each have their own strengths and weaknesses, and your final decision will depend almost entirely on your startup’s needs.

There are some elements for you to consider about:

1. Device features
2. Offline functioning
3. Discoverability
4. Speed
5. Installation
6. Maintenance
7. Platform independence
8. Content restrictions, approval process, and fees
9. Development cost

***

## Summary
There are many different directions in which you can take your app, all of which have their pros and cons.

There will always be some kind of limitation of time or money that will push you to make a certain decision about your app.

What’s important is to spend enough time thinking and calculating before you start building.

***

#### Reference
1. A Guide to Mobile App Development: Web vs. Native vs. Hybrid (https://clearbridgemobile.com/mobile-app-development-native-vs-web-vs-hybrid/#Native_Mobile_Apps)
2. Native vs. Web vs. Hybrid Apps — What’s the Difference?
(https://blog.markgrowth.com/native-vs-web-vs-hybrid-apps-whats-the-difference-1df4c5e4bc50)
3. Native Apps, Web Apps or Hybrid Apps? What’s the Difference? (https://www.mobiloud.com/blog/native-web-or-hybrid-apps/)
4. App Development Decisions: Native, Web or Hybrid?(https://medium.com/@Imaginovation/app-development-decisions-native-web-or-hybrid-31c103f9b4e1)
5. Mobile: Native Apps, Web Apps, and Hybrid Apps (https://www.nngroup.com/articles/mobile-native-apps/)
