📱 BMI Calculator (Android · Kotlin)

A simple and beautiful Android app written in Kotlin to calculate Body Mass Index (BMI) and classify health status based on WHO standards.

✨ Features

⚡ Instant BMI calculation

📏 Metric units (kg, cm)

🎨 Clean, minimal UI with illustrations

🏷️ BMI classification (Underweight, Normal, Overweight, Obese)

📊 Shows results with clear categories

💾 Works fully offline

🛠️ Tech Stack

Language: Kotlin

UI: Android XML + Material Components

Min SDK: 21 (Android 5.0)

IDE: Android Studio

🚀 Installation

Clone this repo:

git clone https://github.com/ErenYeager/BMI-Calculator.git
cd BMI-Calculator-Kotlin


Open the project in Android Studio.

Run the app on an emulator or physical Android device.

📋 Usage
Enter your weight (kg).
Enter your height (cm).
Tap Calculate Your BMI.
View your BMI result and category instantly.

📐 BMI Formula & Categories

Formula:
BMI = weight(kg) / (height(m)²)

WHO Categories:
Category	BMI Range (kg/m²)
Underweight	< 18.5
Normal weight	18.5 – 24.9
Overweight	25.0 – 29.9
Obese	≥ 30.0

📂 Project Structure
app/
├─ java/com/example/bmi
│  └─ MainActivity.kt
├─ res/
│  ├─ layout/activity_main.xml
│  ├─ drawable/ (icons & illustrations)
│  ├─ values/strings.xml
│  └─ values/colors.xml
└─ AndroidManifest.xml

📜 License

MIT License – free to use, modify, and distribute.

⚠️ Disclaimer

This app is for educational/screening purposes only and should not replace professional medical advice.
