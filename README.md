# Android Basics with Compose – Practice Projects

This repository contains multiple Android Studio projects developed as part of the **Android Basics with Compose** training by Google.  
Each project is self-contained and focuses on specific Android and Jetpack Compose concepts such as UI composition, state management, navigation, ViewModel usage, and app architecture.

The projects are organized as **separate folders** within a single repository for easy learning, reference, and portfolio presentation.

## 📂 Project Structure
android-projects/
├── CupCake-App : https://github.com/romilp25z-hub/CupCake-App
├── MarsPhotosApp : https://github.com/romilp25z-hub/MarsPhotosApp.git
├── Race-Tracker-App : https://github.com/romilp25z-hub/Race-Tracker-App
├── Unscramble-Android-App : https://github.com/romilp25z-hub/Unscramble-Android-App
├── basic-android-kotlin-compose-training-dessert-release :
|   https://github.com/ romilp25z-hubbasic-android-kotlin-compose-training-dessert-release
├── basic-android-kotlin-compose-training-lemonade : 
|   https://github.com/romilp25z-hub/basic-android-kotlin-compose-training-lemonade
├── basic-android-kotlin-compose-training-reply-app : 
|   https://github.com/romilp25z-hub/basic-android-kotlin-compose-training-reply-app
└── README.md


Each folder represents an **independent Android Studio project** and can be opened individually in Android Studio.

---

## 📘 Projects Overview

### 1. CupCake-App
**Concepts Covered**
- Jetpack Compose UI
- State hoisting
- Navigation between composables
- ViewModel for UI state
- Unidirectional data flow

**Description**  
A multi-screen app that allows users to order cupcakes by selecting quantity, flavor, and pickup date.  
This project demonstrates how to manage shared UI state across multiple screens using a ViewModel.

---

### 2. MarsPhotosApp
**Concepts Covered**
- REST API consumption
- Retrofit networking
- Repository pattern
- ViewModel + UI state
- Loading, success, and error states

**Description**  
An app that fetches and displays photos from a Mars server.  
It focuses on clean separation between UI and data layers and handling network responses in Compose.

---

### 3. Race-Tracker-App
**Concepts Covered**
- State and recomposition
- Coroutines
- Animations and progress updates
- Lifecycle-aware state handling

**Description**  
A race tracking app that simulates progress for different participants.  
This project helps understand how Compose reacts to state changes over time.

---

### 4. Unscramble-Android-App
**Concepts Covered**
- ViewModel
- StateFlow
- Game logic separation
- Configuration change handling

**Description**  
A word unscrambling game where users guess words.  
The app demonstrates how to keep UI logic separate from business logic and preserve state across rotations.

---

### 5. basic-android-kotlin-compose-training-dessert-release
**Concepts Covered**
- App lifecycle awareness
- Revenue tracking
- Side effects
- Logging and debugging

**Description**  
A dessert-clicker style app that tracks sales and revenue.  
Used to explain Android lifecycle events and how apps behave when moving between foreground and background.

---

### 6. basic-android-kotlin-compose-training-lemonade
**Concepts Covered**
- Basic Compose UI
- Conditional UI rendering
- Remembered state
- User interaction handling

**Description**  
A simple interactive app where users make lemonade through multiple steps.  
Introduces Compose fundamentals and state-driven UI updates.

---

### 7. basic-android-kotlin-compose-training-reply-app
**Concepts Covered**
- Adaptive layouts
- Material Design 3
- Navigation patterns
- Responsive UI (phone/tablet)

**Description**  
An email-style app showcasing adaptive UI patterns.  
Demonstrates how Compose handles different screen sizes and navigation structures.

---

## 🛠️ Tech Stack Used

- **Language:** Kotlin  
- **UI Toolkit:** Jetpack Compose  
- **Architecture:** MVVM  
- **State Management:** ViewModel, StateFlow  
- **Networking:** Retrofit (where applicable)  
- **Design:** Material Design 3  

---

## ▶️ How to Run Any Project

1. Clone the repository:
   ```bash
   git clone https://github.com/romilp25z-hub/android-projects.git
