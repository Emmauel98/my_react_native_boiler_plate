# 🚀 React Native Expo Boilerplate

A powerful React Native Expo boilerplate designed by me to help developers skip setup and focus on building amazing applications.

## ✨ Features
- Pre-configured folder structure  
- Essential packages installed  
- Optimized development experience  
- Ready-to-use navigation and state management  
- ESLint, Prettier, and Husky for clean code  

---

## 📦 Installation

### 1️⃣ Clone the repository
```sh
git clone https://github.com/your-username/your-boilerplate.git
cd your-boilerplate
```

### 2️⃣ Install dependencies
Using npm:
```sh
npm install
```
Or using Yarn:
```sh
yarn install
```

### 3️⃣ Start the development server
```sh
npm start
```
Or:
```sh
yarn start
```
Expo will open a QR code in the terminal or browser. Scan it with your mobile device using the Expo Go app.

---

## 🛠️ Folder Structure
```plaintext
📂 your-boilerplate
 ┣ 📂 src
 ┃ ┣ 📂 components      # Reusable UI components
 ┃ ┣ 📂 screens         # Application screens
 ┃ ┣ 📂 navigation      # React Navigation setup
 ┃ ┣ 📂 hooks           # Custom hooks
 ┃ ┣ 📂 store           # State management
 ┃ ┣ 📂 services        # Api services
 ┃ ┣ 📂 constant        # Some constants used across the whole app
 ┃ ┣ 📂 context         # Context folder
 ┃ ┣ 📂 pages           # Pages
 ┃ ┣ 📂 utils           # Utility functions
 ┃ ┣ 📂 assets          # Images, fonts, and icons
 ┣ 📂 config            # API and environment configuration
 ┣ 📂 scripts           # Custom scripts for automation
 ┣ 📜 App.tsx           # Main app entry file
 ┣ 📜 package.json      # Project dependencies
```

---

## 📌 Built-in Packages
The boilerplate comes with essential libraries pre-installed:

| Feature | Package |
|---------|---------|
| Navigation | `@react-navigation/native` |
| State Management | `react-query` (or Redux if added) |
| Forms & Validation | `react-hook-form` + `yup` |
| HTTP Requests | `axios` |
| UI Components | `react-native-paper` or `react-native-elements` |
| TypeScript Support | `typescript` |
| Linting & Formatting | `eslint`, `prettier`, `husky` |

---

## 📖 Usage Guide

### Adding New Screens
1. Create a new file inside `src/screens/`
2. Example: `ProfileScreen.tsx`
```tsx
import { View, Text } from "react-native";

export default function ProfileScreen() {
  return (
    <View>
      <Text>Profile Screen</Text>
    </View>
  );
}
```
3. Register it in `navigation/AppNavigator.tsx`

---

### Customizing Theme
Modify `theme.ts` in the `config` folder:
```tsx
export const theme = {
  colors: {
    primary: "#3498db",
    secondary: "#2ecc71",
    background: "#f5f5f5",
  },
};
```

---

## 📢 Contributing
Want to improve this boilerplate? Follow these steps:
1. Fork the repo
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m "Added new feature"`)
4. Push to GitHub (`git push origin feature-name`)
5. Create a Pull Request

---

## 📄 License
This project is licensed under the **MIT License**.

---

### 🚀 Start Building Faster with This Boilerplate!
Let me know if you need further improvements! 🚀🔥
