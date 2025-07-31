# 🍼 Pregnancy Vitals Tracker with Reminders  

A simple Android app built using **Kotlin** and **Jetpack Compose** that allows users to log and track pregnancy-related vitals, with reminders to ensure consistent tracking.  

---

## 📌 Features  

✅ **Log Pregnancy Vitals** – Users can record:  
- Blood Pressure (Systolic/Diastolic)  
- Heart Rate  
- Weight  
- Baby Kicks Count  

✅ **Instant Updates** – The vitals list updates live using **StateFlow** or **LiveData**.  

✅ **Reminder Notifications** – Every 5 hours, the app sends a **WorkManager-based notification**:  
- **Title:** _"Time to log your vitals!"_  
- **Message:** _"Stay on top of your health. Please update your vitals now!"_  
- Clicking the notification opens the app directly on the logging screen.  

✅ **MVVM Architecture** – Clean separation of UI and logic for better maintainability.  

✅ **Room Database** – Stores vitals logs locally.  

---

## 🛠 Tech Stack  

- **Language:** Kotlin  
- **UI:** Jetpack Compose  
- **Architecture:** MVVM  
- **Database:** Room  
- **State Management:** StateFlow / LiveData  
- **Background Work:** WorkManager  

---

## 📂 Project Structure  

┣ 📂 data
┃ ┣ 📜 VitalsEntity.kt
┃ ┣ 📜 VitalsDao.kt
┃ ┣ 📜 VitalsDatabase.kt
┣ 📂 repository
┃ ┣ 📜 VitalsRepository.kt
┣ 📂 ui
┃ ┣ 📜 MainScreen.kt
┃ ┣ 📜 AddVitalsDialog.kt
┣ 📂 viewmodel
┃ ┣ 📜 VitalsViewModel.kt
┣ 📂 worker
┃ ┣ 📜 ReminderWorker.kt
┣ 📜 MainActivity.kt
┗ 📜 build.gradle


---

## 🚀 How to Run  

1️⃣ **Clone the repository**  
```bash
git clone https://github.com/yourusername/PregnancyVitalsTracker.git
```

2️⃣ Open in Android Studio

Use Android Studio Arctic Fox or newer

3️⃣ Build & Run

Connect an Android device or start an emulator.

Click ▶️ Run.

🎨 UI/UX Design
The app’s design is based on the provided Figma file.

📸 Screenshots


🎥 Demo  
