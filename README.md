# 🚘 VisionSafe-ADAS: AI Driver Assistance & Road Hazard Detection

<div align="center">
  <img src="https://raw.githubusercontent.com/nourhan255/VisionSafe-ADAS/main/assets/driver-assistance-detection.png" alt="Real-time Detection Sample" width="100%" />
</div>

<br/>

## 🌟 Introduction & Problem Statement
The goal of this project is to enhance road safety by providing drivers with real-time feedback on road danger levels based on the movement of surrounding vehicles. Traditional ADAS systems are often expensive or reactive; this project leverages cutting-edge computer vision to be predictive and accessible. We built an intelligent system capable of analyzing traffic dynamics in real-time to classify road conditions and alert the driver.

## ✨ Key Features
* **Real-time Object Detection:** Detects cars, trucks, motorcycles, and pedestrians with high speed and precision.
* **Dynamic Danger Assessment:** Classifies the current road condition into (Low/Medium/High) danger levels based on relative speeds, distances, and traffic density.
* **Stable Video Inference:** Optimized for minimal flickering, ensuring consistent predictions across video frames.

## 🛠 Tech Stack & Methodology
* **Core Languages:** `Python`, `C++` (for performance-critical parts)
* **ML/DL Frameworks:** `TensorFlow`, `PyTorch`
* **Computer Vision:** `OpenCV`
* **Model:** **YOLO (You Only Look Once)** - Chosen for its superior real-time performance.

---

## 📈 Detailed Methodology & Engineering Focus

### 🧠 Overcoming Overfitting with Regularization
Machine learning models, especially in complex computer vision tasks, are prone to overfitting, where they perform well on training data but fail on new, real-world scenarios. We tackled this by implementing robust **Regularization** techniques.

<div align="center">
  <img src="https://raw.githubusercontent.com/nourhan255/VisionSafe-ADAS/main/assets/overfitting-fix.png" alt="Regularization Analysis Graph" height="200" style="margin-right: 15px;" />
  <p><em>Effect of Regularization: Generalizing the model (green curve) to trap the test data (red points).</em></p>
</div>

### ⏱ Video Inference Stability (Temporal Analysis)
For an ADAS system to be reliable, predictions must be consistent over a sequence of video frames. A noisy, flickering model is unusable. We analyzed the temporal stability of our model on real-world video data.

<div align="center">
  <img src="https://raw.githubusercontent.com/nourhan255/VisionSafe-ADAS/main/assets/frame-predictions.png" alt="Temporal Prediction Stability Graph" height="200" />
  <p><em>Consistency across 140+ frames, showing stable real-time inference.</em></p>
</div>

---

## 🚀 Future Work & Impact
* Integrate depth estimation for precise distance calculation.
* Port the model to run on edge devices like Raspberry Pi.
* This project is a foundational step towards building intelligent, accessible safety solutions for STEM education in Codex Academy.

## 📄 License
This project is licensed under the MIT License - see the `LICENSE` file for details.

## 🤝 Connect with the Developer
* **[Nourhan Ayman](https://github.com/nourhan255):** AI & ML Engineer
* [LinkedIn](https://www.linkedin.com/in/nourhan-ayman-276701198/) | [Twitter](https://twitter.com/NourhanAyma1) | [GitHub](https://github.com/nourhan255)
