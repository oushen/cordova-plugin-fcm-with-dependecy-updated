# Cordova Firebase Cloud Messaging Plugin with Updated Dependencies

A modern, production-ready Cordova plugin that provides seamless integration with Firebase Cloud Messaging (FCM) for push notifications across iOS and Android platforms. This plugin is actively maintained with updated dependencies and enhanced features.

## Key Features

### 🚀 **Easy Integration**
- **Plug & Play Setup** - Minimal configuration required to get push notifications working
- **Cross-Platform Support** - Works seamlessly on both iOS and Android
- **Updated Dependencies** - Uses latest Firebase SDK versions for optimal performance and security

### 📱 **Smart Notification Handling**
- **Foreground Notifications** - Receive notification data directly in JavaScript callbacks when app is active
- **Background/Closed App** - Automatic notification display in system notification bar
- **Tap-to-Open** - App automatically opens and receives notification payload when user taps notification

### 🔧 **Advanced Functionality**
- **Topic Subscriptions** - Subscribe/unsubscribe to Firebase topics for targeted messaging
- **Token Management** - Get and refresh FCM tokens with automatic handling
- **Notification Channels** - Create custom notification channels for Android 8.0+ with specific behaviors
- **Permission Management** - Request and check notification permissions (especially important for iOS)
- **Notification Clearing** - Programmatically clear notifications from the notification center

### 🎯 **Developer-Friendly API**
- **Promise-Based** - Modern async/await support for all API methods
- **Event-Driven** - Listen to notification and token refresh events
- **TypeScript Support** - Full type definitions included
- **Ionic Integration** - Built-in support for Ionic v3, v4, v5 with RxJS observables

### 📋 **Comprehensive Configuration Options**
- **Custom Icons** - Set default notification icons for Android
- **Firebase Versions** - Configure specific Firebase SDK versions
- **Build Tool Versions** - Specify Gradle and Google Services versions
- **iOS Settings** - Configure Firebase Messaging versions for iOS

## Technical Specifications

### **Supported Platforms**
- **Android** - API level 19+ (Android 4.4+)
- **iOS** - iOS 13.0+
- **Cordova** - Version 9.0+

### **Dependencies**
- Firebase Cloud Messaging SDK
- Google Services (Android)
- Firebase iOS SDK
- Updated Gradle build tools

### **SDK Versions (Default)**
- **Android Firebase BOM** - 29.0.1
- **Android FCM SDK** - 23.0.8
- **iOS Firebase Messaging** - ~> 11.15.0
- **Google Services Plugin** - 4.3.4
- **Gradle Tools** - 4.1.0+

*Note: These are configurable through plugin variables during installation*

### **Installation Requirements**
- `google-services.json` file for Android projects
- `GoogleService-Info.plist` file for iOS projects
- Valid Firebase project configuration
- **CocoaPods 1.16.2 or higher** (for iOS builds)

## Use Cases

This plugin is perfect for applications that need:
- **Push notifications** for user engagement
- **Real-time messaging** and alerts
- **Topic-based notifications** for different user groups
- **Cross-platform notification consistency**
- **Modern Firebase integration** with latest features

## Why Choose This Plugin

- ✅ **Actively Maintained** - Regular updates and dependency management
- ✅ **Production Ready** - Battle-tested in real applications
- ✅ **Modern Architecture** - Built with current best practices
- ✅ **Comprehensive Documentation** - Detailed setup and usage guides
- ✅ **Community Support** - Active issue resolution and feature requests
- ✅ **Backward Compatible** - Smooth migration from older FCM plugins

Perfect for developers who want reliable, modern push notification functionality without the headache of managing complex Firebase configurations and dependency conflicts.
