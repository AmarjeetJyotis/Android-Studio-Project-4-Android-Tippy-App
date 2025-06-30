# Tippy - A Simple Tip Calculator for Android

![image](https://github.com/user-attachments/assets/e1bd540a-b1b3-4082-bc99-1e9b496da55f)


![image](https://github.com/user-attachments/assets/3338bfa0-ecaa-4bae-aa91-63d627844241)

# Tippy - Tip Calculator App

Tippy is a simple and user-friendly tip calculator Android application developed using **Kotlin** and **XML** in **Android Studio**. It allows users to calculate the tip amount and the total amount to pay based on a customizable tip percentage.

## 🚀 Features

- Input the base bill amount
- Adjust tip percentage with a slider
- Real-time calculation of:
  - Tip amount
  - Total amount (Base + Tip)
- Dynamic text feedback (e.g., “Great”) based on tip percentage
- Clean and responsive UI design
- Compatible with various Android screen sizes

## 📱 Screenshots

| Main Screen |
|-------------|
| ![Tippy App Screenshot](screenshots/tippy_main.png) |

## 🛠️ Tech Stack

- **Language:** Kotlin
- **UI Design:** XML
- **Architecture:** Android ConstraintLayout
- **IDE:** Android Studio
- **Minimum SDK:** 21 (Lollipop)

## 💡 How It Works

1. The user enters the **Base Amount**.
2. The **Tip Percentage** is adjusted using a slider (SeekBar).
3. The app displays the:
   - **Tip amount** = Base × Tip %
   - **Total amount** = Base + Tip
4. A comment ("Poor", "Good", "Great", etc.) is shown based on the percentage chosen.

## 🧑‍💻 Author

**Amarjeet Kumar**  
**UID:** 21BCS10768  
**Department of Computer Science & Engineering**  
**Chandigarh University**

**Portfolio:** [https://amarjeetkr.vercel.app/](https://amarjeetkr.vercel.app/)  
**LinkTree:** [https://linktr.ee/AmarjeetKumarJyotish](https://linktr.ee/AmarjeetKumarJyotish)  
**GitHub:** [https://github.com/AmarjeetJyotis](https://github.com/AmarjeetJyotis)  
**LinkedIn:** [https://www.linkedin.com/in/amarjeet-jyotish/](https://www.linkedin.com/in/amarjeet-jyotish/)  
**GeeksforGeeks:** [https://www.geeksforgeeks.org/user/amarjeetjyotish/](https://www.geeksforgeeks.org/user/amarjeetjyotish/)  
**LeetCode:** [https://leetcode.com/u/AmarjeetJyotish/](https://leetcode.com/u/AmarjeetJyotish/)



## 📂 Project Structure

app/
├── java/
│ └── com.example.tipcalculator/
│ └── MainActivity.kt
├── res/
│ ├── layout/
│ │ └── activity_main.xml
│ ├── values/
│ │ └── strings.xml, colors.xml, themes.xml
└── AndroidManifest.xml

bash
Copy
Edit

## ✅ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Tippy.git
Open the project in Android Studio.

Sync Gradle and build the project.

Run the app on an emulator or physical device.


📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

