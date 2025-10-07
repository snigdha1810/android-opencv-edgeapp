# Android Edge Detection App (C++ + OpenCV + JNI)

This project demonstrates a simple **real-time edge detection app** built for Android.
The app captures frames from the camera, processes them with **OpenCV (C++)** through **JNI**, and displays the processed output using **OpenGL ES**.

---

## 🚀 Features

* Real-time camera preview using Android Camera2 API
* Edge detection with OpenCV (Canny algorithm)
* Native C++ processing via JNI
* OpenGL-based rendering
* Simple TypeScript web viewer (for sample frame display)

---

## 🧩 Folder structure

```
app/                    # Android source code
jni/                    # Native C++ code (OpenCV)
web/                    # Simple TypeScript viewer
screenshots/            # Output images / GIFs
```

---

## ⚙️ Setup Instructions

1. Clone the repository

   ```
   git clone https://github.com/YOURUSERNAME/android-opencv-edgeapp.git
   ```
2. Open in Android Studio
3. Sync Gradle and run the app (requires OpenCV SDK)

---

## 🖼 Screenshots

Add screenshots in `/screenshots/` folder.

Example:

```
screenshots/
 ├─ app_preview.png
 ├─ edges_output.gif
```

---

## 🧠 Architecture Overview

**Java/Kotlin layer:** handles camera and UI
**C++ layer:** uses OpenCV for image processing
**JNI bridge:** connects Android and native C++
**Web viewer:** displays sample frame with TypeScript

---

## 🧾 Commit History Example

* feat: add camera preview logic
* feat: integrate OpenCV native processing
* fix: update CMake for NDK 23
* docs: add README and screenshots

---

## 👩‍💻 Author

Unnava Snigdha
SRM University AP
B.Tech — Android OpenCV Assignment Submission

---
