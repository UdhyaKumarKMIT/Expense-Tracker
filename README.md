
# Expense Tracker

A **Expense Tracker mobile application** built using **React Native (Expo)** that helps users track monthly expenses category-wise with intuitive charts and history insights.  
The app stores all data locally on the device, ensuring privacy, speed, and offline usability.  
Designed with a minimal and responsive UI to promote mindful spending — *“Spend wisely.”*

---

## 🛠️ Tech Stack

- **Framework:** React Native (Expo)
- **Language:** TypeScript
- **Navigation:** React Navigation
- **State Management:** React Context API
- **Local Storage:** AsyncStorage
- **Charts & Visualization:** react-native-chart-kit
- **UI Components:** react-native-paper
- **Icons:** react-native-vector-icons
- **Platform Support:** Android, Web (Expo)

---

## ✨ Features

- 📅 **Monthly Expense Tracking** with automatic month-wise segregation  
- 🧾 **Category-based Expenses** (Food, Snacks, Travel, Bills, Cash / GPay)  
- ➕ **Add Expense Form** with validation and payment mode selection  
- 📊 **Visual Analytics** using Pie Charts for better financial insights  
- 🕘 **Expense History View** with previous month selection  
- 💾 **Offline Storage** using mobile local storage (no backend required)  
- 🎨 **Clean & Responsive UI** optimized for mobile screens  
- 🚀 **Fast App Launch** with a custom splash screen displaying *“Spend wisely”*

---

## 📁 Project Structure

```

src/
├── screens/        # App screens (Splash, Home, Add Expense, History)
├── components/     # Reusable UI components
├── context/        # Global state management
├── storage/        # AsyncStorage logic
├── utils/          # Helpers & constants
└── navigation/     # App navigation setup

````

---

## ▶️ Getting Started

### Prerequisites
- Node.js (18 LTS recommended)
- Expo CLI
- Expo Go app (for mobile testing)

### Run the App
```bash
npm install
npx expo start
````

Press:

* `w` → Web
* Scan QR → Mobile (Expo Go)

---

## 🔒 Data Privacy

All expense data is stored **locally on the device**.
No internet connection or external database is required.

---

---

## 👨‍💻 Author

Developed as a **personal productivity & learning project** using modern mobile development practices with React Native.

---

## 📄 License

This project is open-source and available under the **MIT License**.

````
