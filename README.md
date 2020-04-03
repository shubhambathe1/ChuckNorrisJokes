<<<<<<< HEAD
# APICALLSBOSS [![Flutter logo][]][flutter.dev]

Chuck Norris - API Flutter Calls Tutorial Like a Boss

Demo app to showcase the use of Flutter API calls using Bloc architecture.

Tutorial can be found here: 
##
https://medium.com/platform45/flutter-handling-your-network-api-calls-like-a-boss-9093c71a7c97

### Screenshots

<img src="assets/screenshots/screen1.jpg" height="600em" /> <img src="assets/screenshots/screen2.jpg" height="600em" />
 
    
# [![Flutter logo][]][flutter.dev]

[![Build Status - Cirrus][]][Build status]
[![Gitter Channel][]][Gitter badge]

Flutter is Google's mobile app SDK for crafting high-quality native interfaces
on iOS and Android in record time. Flutter works with existing code, is used by
developers and organizations around the world, and is free and open source.

## Documentation

* [Install Flutter](https://flutter.dev/get-started/)
* [Flutter documentation](https://flutter.dev/docs)
* [Development wiki](https://github.com/flutter/flutter/wiki)
* [Contributing to Flutter](https://github.com/flutter/flutter/blob/master/CONTRIBUTING.md)

For announcements about new releases and breaking changes, follow the
[flutter-announce@googlegroups.com](https://groups.google.com/forum/#!forum/flutter-announce)
mailing list.

## About Flutter

We think Flutter will help you create beautiful, fast apps, with a productive,
extensible and open development model.

### Beautiful apps

We want to enable designers to deliver their full creative vision without being
forced to water it down due to limitations of the underlying framework.
Flutter's [layered architecture] gives you control over every pixel on the
screen, and its powerful compositing capabilities let you overlay and animate
graphics, video, text and controls without limitation. Flutter includes a full
[set of widgets][widget catalog] that deliver pixel-perfect experiences on both
iOS and Android.

### Fast apps

Flutter is fast. It's powered by the same hardware-accelerated [Skia] 2D
graphics library that underpins Chrome and Android. We architected Flutter to
support glitch-free, jank-free graphics at the native speed of your device.
Flutter code is powered by the world-class [Dart platform], which enables
compilation to native 32-bit and 64-bit ARM code for iOS and Android.

### Productive development

Flutter offers stateful hot reload, allowing you to make changes to your code
and see the results instantly without restarting your app or losing its state.

### Extensible and open model

Flutter works with any development tool, but includes editor plug-ins for both
[Visual Studio Code] and [IntelliJ / Android Studio]. Flutter provides
[thousands of packages][Flutter packages] to speed your development, regardless
of your target platform. And accessing platform features is easy. Here is a
snippet from our [interop example]:

```dart
Future<void> getBatteryLevel() async {
  var batteryLevel = 'unknown';
  try {
    int result = await methodChannel.invokeMethod('getBatteryLevel');
    batteryLevel = 'Battery level: $result%';
  } on PlatformException {
    batteryLevel = 'Failed to get battery level.';
  }
  setState(() {
    _batteryLevel = batteryLevel;
  });
}
```

Flutter is a fully open source project, and we welcome contributions.
Information on how to get started can be found at our
[contributor guide](CONTRIBUTING.md).

[Flutter logo]: https://raw.githubusercontent.com/flutter/website/master/src/_assets/image/flutter-lockup.png
[flutter.dev]: https://flutter.dev
[Build Status - Cirrus]: https://api.cirrus-ci.com/github/flutter/flutter.svg
[Build status]: https://cirrus-ci.com/github/flutter/flutter/master
[Gitter Channel]: https://badges.gitter.im/flutter/flutter.svg
[Gitter badge]: https://gitter.im/flutter/flutter?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge
=======
# ChuckNorrisJokes
A small fun Chuck Norris facts app in Flutter using this endpoint:- "https://api.chucknorris.io/" . The app is designed by considering following points: BLOC Architecture and Project setup API calls setup Repos and BLOCS UI.
>>>>>>> 42bd21cd15da057960d0242eb591a18b3874fe95
