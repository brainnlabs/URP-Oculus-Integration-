# URP-Oculus-Integration-
Adaptation of URP for Oculus Quest in Unity

---

# Resources

Youtube Video:

[2020, TensorFlow 2.2 NVIDIA GPU (CUDA)/CPU, Keras, & Python 3.7 in Linux Ubuntu](https://www.youtube.com/watch?v=dj-Jntz-74g&t=357s)

---

# Required Software versions:

+ **Unity 2021 or 2022**

---

# Installation Steps

1.- Create new project in Unity. 

2.- Choose template: **3D Sample Scene (URP)**

3.- Switch to Android Platform: go to **file** -> **Build Settings** -> **Android** -> **Switch Platform**

4.- Create a new folder named **URP** and move all the installed asset folders.

5.- Install **Oculus Integration** package: go to **Window** -> **Package Manager** -> **Packages: in Project** -> **My Assets** -> **Oculus Integration** -> **Import**

6.- Modify Project Setting: **Edit** -> **Project Settings**

+ **XR Plugin Managment:** -> **Install XR Plugin Managment**
  +  **Android = Oculus**

+ **Player:**
  +  **Color Space = Linear**
  +  **Color Gamut = sRGB**
  +  **Minimum API Level = Android 10 (API Level 29)**
  +  **Scripting Backend = IL2CPP**
  +  **Target Architectures = ARM64**

7.- Modify URP Settings: **UniversalRP-MediumQuality**

+ **Quality**
  + **Anti Aliasing (MSAA) = 4x  

8.- Convert all Oculus Integration Assets made with Built-in to URP

+ **Window** -> **Rendering** -> **Rendering Pipeline Converter**
+ Drop Down Menu -> **Built-in to URP
+ **Choose all Asset** -> **Initialize Converters** -> **Convert Assets**


