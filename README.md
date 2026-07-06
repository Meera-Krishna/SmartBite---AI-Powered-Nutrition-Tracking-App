# 🥗 SmartBite – AI-Powered Nutrition Tracking App

SmartBite is an AI-powered Android application designed to help users maintain a healthy lifestyle by tracking their daily nutrition and calories. The application leverages **Google ML Kit** for intelligent food image recognition, enabling users to scan meals, monitor nutritional intake, and receive personalized insights through a clean and intuitive Android interface.

---

## 📱 Features

* 📷 Scan food images using **Google ML Kit Image Labeling**.
* 🍽️ Track daily meals with calorie and nutritional information.
* 📊 Monitor calorie intake and nutrition progress through an interactive dashboard.
* 💧 Record daily water intake to maintain hydration goals.
* 📝 Maintain complete meal history for future reference.
* 📄 Generate downloadable nutrition reports in PDF format.
* 🔔 Receive meal and water reminders using background notifications.
* 🔐 Secure user authentication with Firebase Authentication.
* ☁️ Store user profiles and nutrition data securely using Firebase Firestore.

---

## 🛠 Tech Stack

### Language

* Kotlin

### UI

* Jetpack Compose
* Material Design 3

### Architecture

* MVVM (Model-View-ViewModel)

### Database & Authentication

* Firebase Authentication
* Firebase Firestore

### AI & Android Components

* Google ML Kit (Image Labeling)
* WorkManager
* Camera Integration

### Additional Libraries

* iTextPDF
* Coil

---

## 📂 Project Structure

```text
SmartBite/
│
├── app/
├── ui/
│   ├── screens/
│   ├── components/
│   └── navigation/
├── viewmodel/
├── repository/
├── model/
├── firebase/
├── mlkit/
├── worker/
├── utils/
└── README.md
```

---

## 🚀 Application Workflow

1. User registers or logs in using Firebase Authentication.
2. Profile information is stored in Firebase Firestore.
3. User captures or uploads a food image.
4. Google ML Kit identifies the food item from the image.
5. Nutritional information is displayed and logged.
6. Daily calorie and water intake are updated automatically.
7. Users can view meal history, download nutrition reports, and receive reminder notifications.

---

## 💡 Key Highlights

* Developed using **Kotlin** and **Jetpack Compose** for a modern Android experience.
* Integrated **Google ML Kit** to enable AI-powered food image recognition.
* Implemented **MVVM architecture** for scalable and maintainable code.
* Leveraged **Firebase Authentication** and **Cloud Firestore** for secure user management and cloud data storage.
* Utilized **WorkManager** for scheduled meal and hydration reminders.
* Generated downloadable nutrition reports using **iTextPDF**.

---

## 🔮 Future Enhancements

* Personalized diet recommendations based on user goals.
* Weekly and monthly nutrition analytics.
* Barcode scanning for packaged food items.
* AI-powered meal recommendations.
* Integration with fitness wearables and Google Fit.

---

## 📸 Screenshots


* Splash Screen
* Login & Registration
* Home Dashboard
* Food Scanner
* Meal History
* Water Tracker
* Nutrition Report
* Profile

---

## 👩‍💻 Author

**Meera Krishna**

B.Tech (Computer Science & Engineering)

Android Developer | AI Enthusiast

---

## ⭐ If you found this project useful, don't forget to star the repository!

