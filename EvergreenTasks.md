# Evergreen Tasks

Here's a list of tasks that you can come back to or complete in-between other tasks, during times when you're blocked, or wait until the end of app development.

- Splash screens: this is usually an iOS only task, but you can do both [here](https://www.reactnativeschool.com/simple-splash-launch-boot-screen-in-react-native-ios-and-android) is an example.
- Clearing the keyboard from the inputs: this is something you need to ensure in _every app_ that has inputs, this will _drastically_ impact user experience. There are a variety of ways to make this happen, depending on what your needs are. Some apps have custom build components for this purpose, here are a few libraries of interest, [keyboard spacer](https://github.com/Andr3wHur5t/react-native-keyboard-spacer) & `react-native-keyboard-aware-scroll-view` [here](https://github.com/APSL/react-native-keyboard-aware-scroll-view).
- Checking breaking changes on different sized iOS devices / Android devices
- Ensure all the titles are the right _color_ and _font size_
- Ensure you've removed inline styling from most components
- Loader / loading screen - you'll inevitably need _some_ sort of loading screen, it can be a text placeholder or a [default](https://reactnative.dev/docs/activityindicator), just depends on your needs, [here](https://www.codedaily.io/courses/Master-React-Native-Animations) is a free course on the Animated API in case you want to animate an image/logo
- Ensure that headers / footers clear the nothes on multiple devices
- If you're using GitHub for the project, create a `PR template` file for the repo
- Create local storage utility functions so you don't have to import Async Storage everywhere
- Create utility functions to format titles, names, dates
- Ensure that all titles/icons/text that should be _center aligned in a row_ is not off on all devices (phone/tablet) and platforms (iOS/Android/etc)
- Ensure that the tab icons (if there are any) toggle color when they are focused/unfocused
- Use `NetInfo` to add an error screen in case the Internet connection goes out
