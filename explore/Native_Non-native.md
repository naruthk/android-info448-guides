# Native vs. Non-Native Apps

It all begins with frameworks. A framework that is closer to the hardware is considered to be more native.

## Level of Nativeness

- C++ app (most native)
- Java/Kotlin (less native)
- Cordova (least native)

## Benefits of Native Apps

- More access to hardware features
- Runs more efficiently because of lower overhead for simulation and translation between different languages
- Extremely hard to develop native apps especially if not familiar with the language

## Benefits of Non-Native Apps

- Easy to write + read
- Needs less understanding of the hardware
- More portable (can be run on multiple platforms with just one language/framework being used)
- Even a web developer (using JavaScript) can create mobile app using any available frameworks

## Cons of Native Apps

- Higher learning curve
- One language, one platform (Java/Kotlin for Android, C++/Swift for iOS)

## Cons of Non-Native Apps

- Not much hardware support
- Not the best user interfaces (especially for Ionic and PhoneGap)

## Popular Frameworks

### Ionic / PhoneGap

Ionic: https://ionicframework.com/
PhoneGap: http://phonegap.com/ (Less popular)

- Requires the use of a WebView framework (this layer lies in between the Native layer and the development framework itself)
- Allows web developers to develop mobile apps using HTML/CSS/JavaScript
- Apps published using these two frameworks can run on both Android and iOS

### React Native

Website: https://facebook.github.io/react-native/

Made by Facebook

- A better framework than both Ionic and PhoneGap because React Native is “more native” than them. In fact, it runs directly in the same layer as the Native framework layer.
- React Native renders user interfaces using the actual native UI widgets in each platform, making the overall feel of the app so much more real
- Uses JavaScript for development, HTML for content, and CSS for styling

---

Source: [https://uxplanet.org/react-native-vs-cordova-phonegap-ionic-etc-2f85d9651605](https://uxplanet.org/react-native-vs-cordova-phonegap-ionic-etc-2f85d9651605)