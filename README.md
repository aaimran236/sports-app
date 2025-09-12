Sports App - Adaptive UI for Android
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com)
[![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack%2520Compose-4285F4?style=for-the-badge&logo=jetpack-compose&logoColor=white)](https://developer.android.com/jetpack/compose)
==================================
This repository contains a practice project for building an adaptive Android app using Jetpack Compose. The goal of this project is to take a pre-existing mobile-first app and adapt its layout and navigation to provide a better user experience on large-screen devices, such as tablets and foldable phones.

### Project Overview

This project is a **Sports app** that has been adapted to provide an optimal user experience across different screen sizes, from **mobile phones** to **large tablets** and **foldables**.

Starting with a **mobile-first design**, the app's layout and navigation have been modified to implement an **adaptive two-pane layout** for large screens.  

- The **list of sports** is displayed in a dedicated list pane on the left.  
- The **details of the selected sport** are displayed in a detail pane on the right.  
- Content is updated within the same screen, eliminating the need for navigation to a new screen.  

### Key Concepts & Features

This project reinforces several concepts from the **Android Basics in Compose** pathway and modern Android development practices:

- **Window Size Classes** – Determines screen size using `WindowWidthSizeClass` and adapts layouts accordingly.  
- **Canonical Layouts** – Implements list–detail (two-pane) patterns for larger screens.  
- **Adaptive Navigation** – Handles navigation changes based on screen size (new screen on small devices vs. pane updates on large screens).  
- **State Hoisting** – Shares state (e.g., selected sport) between list and detail panes via hoisted state.  
- **Responsive Design** – Provides an optimized UI for all device sizes.  
- **Modern Android Development** – Built with **Jetpack Compose** and **Material Design 3**.

## 📷 Screenshots

### Mobile View (Compact) 
<img width="300" height="852" alt="Screenshot 2025-09-12 200847" src="https://github.com/user-attachments/assets/2fcc0a1d-464b-4372-bd75-7d2c9531e39a" />

### Tablet View (Expanded)
<img width="1369" height="860" alt="Screenshot 2025-09-12 212912" src="https://github.com/user-attachments/assets/3feaa200-3512-4c1f-a22a-1290bf65f3e8" />


## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/aaimran236/sports-app.git
2. Open the project in Android Studio

3. Build and run the app on your preferred device or emulator

### Acknowledgments

## 💡 Credits & Acknowledgments

- [Practice: Build Sports App (Codelab)](https://developer.android.com/codelabs/basic-android-kotlin-compose-practice-sports-app?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-compose-unit-4-pathway-3%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-compose-practice-sports-app)  
- [Android Jetpack Compose team](https://developer.android.com/jetpack/compose)  
- [Material Design 3 guidelines](https://m3.material.io/)  
- [Android Developers documentation](https://developer.android.com/docs)  

