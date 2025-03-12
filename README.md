🧬 Unity AR DNA Model – Augmented Reality Application
This repository contains a Unity-based AR application that visualizes a 3D DNA model with interactive controls. The DNA model, sourced from Sketchfab, is available for download in dna.zip 
🔹 Project Overview
Engine: Unity (2021+ recommended)
AR Framework: Vuforia Engine
3D Model Source: Sketchfab (dna.zip)
Interactions: Zoom, Slider-based rotation
Platform: Android/iOS (Built for AR-capable devices)


### **Technical Breakdown of the Unity AR DNA Model Application**  

1️⃣ **AR Framework – Vuforia Engine**  
   - Uses **Vuforia Image Targeting** to detect a predefined **marker** (image target or ground plane).  
   - Once recognized, the **3D DNA model** is instantiated in the AR scene.  

2️⃣ **3D Model Integration**  
   - The **DNA model** (downloaded from Sketchfab) is imported as a **FBX/glTF file**.  
   - Applied **Unity materials and shaders** for realistic rendering.  
   

3️⃣ **User Interaction Mechanisms**  
   - **Pinch-to-Zoom**: Adjusts the scale of the DNA model dynamically.  
  
   - **Slider-Based Roatation**

4️⃣ **Scene Setup in Unity**  
   - **ARCamera**: Handles **Vuforia tracking** and camera feed overlay.  
   - **ImageTarget / Ground Plane**: Acts as the anchor for the DNA model in AR space.  
   - **Canvas UI**: Contains **buttons, sliders, and interaction controls**.  

5️⃣ **Deployment & Compatibility**  
   - Built for **Android & iOS (AR-capable devices)**.  
   - Uses **Vuforia’s ARCore & ARKit** support for stable tracking.  
   - Exported as an APK (or Xcode project for iOS).  
