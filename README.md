# MOSSETrackerApp

A Visual Object Tracking application using the **MOSSE (Minimum Output Sum of Squared Error)** algorithm implemented in **C++ with OpenCV** and **MFC (Microsoft Foundation Class Library)**.

## 📌 Abstract

This project demonstrates real-time visual object tracking using adaptive correlation filters. It implements the MOSSE algorithm, known for its high speed and robustness, within a GUI-based MFC SDI application. The application supports webcam and video input, manual ROI selection, performance metrics, and optional video saving.

---

## 🎯 Features

- ✅ MOSSE Tracking Algorithm (real-time)
- ✅ Manual ROI selection with mouse
- ✅ Webcam & Video File input
- ✅ Pause / Resume tracking
- ✅ Reset ROI on demand
- ✅ Save tracking video to disk
- ✅ Confidence logging with timestamps
- ✅ FPS overlay on screen
- ✅ Toolbar and Menu integration

---

## 🛠 Prerequisites

- **Operating System**: Windows 10 / 11 (64-bit)
- **Visual Studio 2015 or later** with MFC support
- **OpenCV 4.1.1** installed and configured
- CMake (if building manually outside Visual Studio)

---

## 🔧 Project Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/MOSSETrackerApp.git
   cd MOSSETrackerApp

2. **Open in Visual Studio**

  Open MOSSETrackerApp.sln in Visual Studio 2015 or newer.

3. **Configure OpenCV Paths**

  Set OpenCV include/lib paths:
  
      C/C++ > General > Additional Include Directories
      Linker > General > Additional Library Directories

4. **Link required OpenCV .lib files in:**

        Linker > Input > Additional Dependencies

   Example:
   opencv_world411.lib

5. **Set Path**

        Search Edit Environmental Variables > Advanced > Environmental Varibles > System Variables > Path > Edit > New > Add the Bin Path of OpenCV to it

7. **Build the Project**

         Set configuration to Release x64
         Click Build > Build Solution (Ctrl+Shift+B)
         Run Local Debugger or Open .exe file from Release Folder

