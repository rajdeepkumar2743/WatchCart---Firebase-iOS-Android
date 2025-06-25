# WatchCart - Firebase (iOS & Android)

A modern e-commerce mobile app boilerplate using **React Native**, **Firebase**, and **Redux**.

## 🔥 Features

* Login / Signup (Email + Social)
* Forgot Password (Recovery)
* Product Listings with Filters & Categories
* Add to Cart / Remove from Cart
* Wishlist (with Redux Persist)
* Razorpay Payment Integration
* Order History & Tracking
* Product Reviews (Write & View)
* Multiple Shipping Addresses
* Profile Management
* Google Ads Integration (update in `AndroidManifest.xml` and `Info.plist`)
* Coming Soon: 🔍 Search Function

## 📹 Screen Recording

![Video](/screens-shots/video_.gif?raw=true "Run time Video")

## 🧰 Requirements

* [Node.js](https://nodejs.org) `v18.x` or newer
* [React Native CLI](https://reactnative.dev/docs/environment-setup)
* [Android Studio](https://developer.android.com/studio)
* [Xcode](https://developer.apple.com/xcode/) for iOS development

## 🧱 Tech Stack 

* **React Native** `0.72.10`
* **React** `18.2.0`
* **Redux** `4.2.1` & **Redux Saga** `1.2.1`
* **Firebase** `18.4.0` (Auth + Firestore)
* **Razorpay** Payment SDK `2.2.8`
* **Navigation**: React Navigation v6
* **UI Libraries**: `react-native-vector-icons`, `react-native-paper`, `react-native-ratings`, `react-native-step-indicator`, etc.
* **Async Storage**: `@react-native-async-storage/async-storage`
* **Testing**: Jest `29.6.2`

## 📦 Key Dependencies (Select)

* `@react-native-firebase/app`, `auth`, `firestore`
* `@react-navigation/native`, `stack`, `bottom-tabs`
* `react-native-svg`, `reanimated`, `gesture-handler`, `screens`
* `redux-persist`, `react-redux`

## 🚀 Getting Started

### 1. Clone & Install

```bash
git clone https://github.com/rajdeepkumar2743/Watchcart---Firebase-IOS-Android.git
cd Watchcart---Firebase-IOS-Android
npm install
```

### 2. iOS Setup

```bash
cd ios && pod install && cd ..
react-native run-ios
```

### 3. Android Setup

Ensure your emulator is running or a device is connected.

```bash
react-native run-android
```

### 4. Decide Navigation Type

Controlled by `navigationTypeTabs` in `app.json`:

```json
{
  "navigationTypeTabs": true
}
```

## ✏️ Rename Your App

```bash
npm install -g react-native-rename
git checkout -b rename-app
react-native-rename "NewAppName" -b com.newcompany.newapp
```

---

