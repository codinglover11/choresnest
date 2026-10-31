# 🏡 ChoresNest

### Your Family. Your Tasks. One Organized Home.

**ChoresNest** is a free, all-in-one family organizer designed to make everyday household management easier. Bring your family together to organize chores, coordinate calendars, manage grocery lists, track shared expenses, and keep important notes — all in one place.

🌐 **Website:** [choresnest.com](https://choresnest.com)

---

## ✨ Features

- 🧹 **Shared Chores** – Organize household tasks and share responsibilities.
- 📅 **Family Calendar** – Keep track of events, schedules, and important dates.
- 🛒 **Grocery Lists** – Create and manage shared shopping lists.
- 💰 **Expense Tracking** – Keep household expenses organized.
- 📝 **Shared Notes** – Store important family information and reminders.
- 🏠 **Everyday Planning** – Bring household activities together in one workspace.

---

## 🛠️ Tech Stack

- **Framework:** React Native
- **Language:** TypeScript
- **Project Setup:** React Native Community CLI
- **Platforms:** Android & iOS

---

# 🚀 Getting Started

Follow these steps to set up and run ChoresNest locally.

## 📋 Prerequisites

Before getting started, make sure you have completed the official React Native environment setup.

- [Node.js](https://nodejs.org/)
- npm or Yarn
- [React Native Development Environment](https://reactnative.dev/docs/set-up-your-environment)
- Android Studio (for Android development)
- Xcode (for iOS development on macOS)
- CocoaPods (for iOS dependencies)

---

## 1️⃣ Clone the Repository

```bash
git clone <YOUR_REPOSITORY_URL>
```

Navigate into the project directory:

```bash
cd ChoresNest
```

Install project dependencies:

```bash
npm install
```

---

## 2️⃣ Start Metro

Metro is the JavaScript bundler used by React Native to build and serve your application during development.

From the project root, run:

```bash
npm start
```

Or using Yarn:

```bash
yarn start
```

Keep the Metro terminal running while building the application.

---

## 3️⃣ Run the Application

Open another terminal window from the project root.

### 🤖 Android

Using npm:

```bash
npm run android
```

Using Yarn:

```bash
yarn android
```

### 🍎 iOS

First, install CocoaPods dependencies.

Install Ruby dependencies (required on the first setup):

```bash
bundle install
```

Install iOS native dependencies:

```bash
bundle exec pod install
```

Now run the application:

Using npm:

```bash
npm run ios
```

Using Yarn:

```bash
yarn ios
```

> **Note:** iOS development requires macOS and Xcode.

---

## 4️⃣ Start Building & Modifying

Once the application is running, you can start customizing it.

1. Open `App.tsx` in your preferred code editor.
2. Make changes to the application.
3. Save the file.
4. React Native automatically refreshes the application using **Fast Refresh**.

### 🔄 Reload the Application

| Platform | Reload Shortcut |
|---|---|
| Android | Press `R` twice |
| Android Dev Menu | `Ctrl + M` (Windows/Linux) |
| iOS Simulator | Press `R` |

You can also access the Developer Menu to reload or debug the application.

---

## 📁 Project Structure

```text
ChoresNest/
│
├── android/          # Android native project
├── ios/              # iOS native project
├── node_modules/     # Project dependencies
├── App.tsx           # Application entry component
├── index.js          # Application registration
├── package.json      # Dependencies and scripts
├── tsconfig.json     # TypeScript configuration
├── babel.config.js   # Babel configuration
├── metro.config.js   # Metro bundler configuration
└── README.md         # Project documentation
```

---

## 🧰 Troubleshooting

Facing issues while setting up or running the project?

Here are some useful resources:

- [React Native Troubleshooting](https://reactnative.dev/docs/troubleshooting)
- [Environment Setup](https://reactnative.dev/docs/set-up-your-environment)
- [Fast Refresh Guide](https://reactnative.dev/docs/fast-refresh)
- [CocoaPods Getting Started](https://guides.cocoapods.org/using/getting-started.html)

### Common Development Commands

| Command | Description |
|---|---|
| `npm install` | Install dependencies |
| `npm start` | Start Metro |
| `npm run android` | Run Android application |
| `npm run ios` | Run iOS application |
| `npm test` | Run tests, if configured |
| `npm run lint` | Run linting, if configured |

---

## 📚 Useful Resources

Explore these resources to learn more about the technologies used:

- [React Native Official Website](https://reactnative.dev/)
- [React Native Documentation](https://reactnative.dev/docs/getting-started)
- [React Native Integration Guide](https://reactnative.dev/docs/integration-with-existing-apps)
- [React Native Blog](https://reactnative.dev/blog)
- [React Native Community CLI](https://github.com/react-native-community/cli)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)

---

## 🎯 Our Vision

Managing a household shouldn't feel like another full-time job.

ChoresNest aims to make family coordination simpler by bringing everyday responsibilities, plans, and shared information into one convenient place.

**Less chaos. More coordination. A happier home. ❤️**

---

🌐 **Explore ChoresNest:** [https://choresnest.com](https://choresnest.com)

*Built to bring families closer through better organization.*
