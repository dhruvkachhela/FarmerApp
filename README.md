# 🌾 FarmerApp

A mobile app built with React Native and Expo that connects farmers with buyers. Farmers can list their crops, manage availability, and chat with interested buyers — all from their phone.

---

## 📱 Features

- **Authentication** — Login and Register screens
- **Crop Listings** — View all available crops with price, quantity, and location
- **Add a Crop** — Farmers can post new crop listings
- **Mark as Sold Out** — Toggle crop availability in real time
- **Remove Listing** — Delete a crop listing permanently
- **Messaging** — Chat screen between farmers and buyers
- **Profile** — User profile screen

---

## 🛠️ Built With

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [React Navigation](https://reactnavigation.org/) — Stack + Bottom Tab navigation
- [Expo Vector Icons](https://icons.expo.fyi/)
- JavaScript (ES6+)

---

## 🚀 Getting Started

### Prerequisites
- Node.js installed
- Expo Go app on your phone ([Android](https://play.google.com/store/apps/details?id=host.exp.exponent) / [iOS](https://apps.apple.com/app/expo-go/id982107779))

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/dhruvkachhela/farmer-app.git
   cd farmer-app
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Start the app
   ```bash
   npx expo start
   ```

4. Scan the QR code with Expo Go on your phone — or press `w` to open in browser

---

## 📂 Project Structure

```
farmer-app/
├── App.js              # Root component, navigation setup
├── CropContext.js      # Global state management for crop listings
├── index.js            # Entry point
├── screens/            # All screen components
│   ├── HomeScreen
│   ├── LoginScreen
│   ├── RegisterScreen
│   ├── ProfileScreen
│   ├── AddCropScreen
│   ├── CropDetailScreen
│   ├── ChatScreen
│   └── ChatsListScreen
└── assets/             # Icons and images
```

---

## 👨‍💻 Developer

**Dhruv Kachhela**
2nd Year — Engineering Physics, IIT Indore
[GitHub](https://github.com/dhruvkachhela) · [dhruvkachhela2006@gmail.com](mailto:dhruvkachhela2006@gmail.com)
