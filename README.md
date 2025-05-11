This is the application which is Shop Smart Mini

🚀 Features:

📦 Product listing

🛒 Add/remove items from cart

👤 Profile screen with avatar upload

Library	Purpose & Why I Chose It

React Native -	Core framework for building cross-platform apps with a single codebase.
@reduxjs/toolkit -	Simplifies Redux setup and improves readability and maintainability with createSlice, createAsyncThunk.
react-redux - 	Connects Redux state to React components efficiently.
redux-persist	- Persists Redux state (like cart data and auth status) across app restarts.
axios	- For clean and flexible HTTP requests with built-in interceptor support.
@react-navigation/native	- Provides a declarative API for navigation and works well with stacks, tabs, and nested navigators.
@react-navigation/native-stack	- Used for faster, native-stack-based navigation transitions.
@react-navigation/bottom-tabs	- For clean bottom tab navigation, ideal for e-commerce app structure.
@react-native-async-storage/async-storage	- For storing key user preferences and persisted login state.
@react-native-google-signin/google-signin	- Enables easy integration of Google Sign-In for authentication.
react-native-image-picker	- Allows users to pick and upload avatars or profile images.
react-native-vector-icons	- Adds beautiful and consistent icons across the app.
react-native-floating-label-input	- Provides a modern UI input field with a floating label, enhancing form UX.
react-native-svg	- Enables custom SVG rendering for elements like icons and barcodes.


📂 Folder Structure:

src/
├── components/         # Reusable components
├── screens/            # Screen-level components (Home, Cart, Profile)
├── store/              # Redux slices and configuration
├── themes/             # Reusable colors
├── navigation/         # Navigation configuration
├── redux/slice/        # API & helpers
└── App.tsx             # Entry point


Architecture:

1. Modular, feature-based structure for scalability.

2. Redux Toolkit with createSlice and createAsyncThunk.

3. Reusable Component


✅ Completed Tasks:

 - Product list with add/remove cart

 - Product Details Screen

 - Profile screen with editable fields and avatar upload

 - Responsive UI for Android and iOS

 - APK & IPA build

 - Demo video and screenshots included




This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# Getting Started

> **Note**: Make sure you have completed the [Set Up Your Environment](https://reactnative.dev/docs/set-up-your-environment) guide before proceeding.

## Step 1: Start Metro

First, you will need to run **Metro**, the JavaScript build tool for React Native.

To start the Metro dev server, run the following command from the root of your React Native project:

```sh
# Using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Build and run your app

With Metro running, open a new terminal window/pane from the root of your React Native project, and use one of the following commands to build and run your Android or iOS app:

### Android

```sh
# Using npm
npm run android

# OR using Yarn
yarn android
```

### iOS

For iOS, remember to install CocoaPods dependencies (this only needs to be run on first clone or after updating native deps).

The first time you create a new project, run the Ruby bundler to install CocoaPods itself:

```sh
bundle install
```

Then, and every time you update your native dependencies, run:

```sh
bundle exec pod install
```

For more information, please visit [CocoaPods Getting Started guide](https://guides.cocoapods.org/using/getting-started.html).

```sh
# Using npm
npm run ios

# OR using Yarn
yarn ios
```



