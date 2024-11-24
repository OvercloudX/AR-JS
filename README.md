# AR.js Phare Project

## 📖 Project Description
This project demonstrates an **Augmented Reality (AR)** application using **AR.js** to display a 3D model of a historical building at a specific location. The AR experience is triggered by recognizing a custom marker or, alternatively, by using GPS-based positioning.

## ✨ Features
- **Marker-based AR**: Displays a 3D model when a specific marker is recognized.
- **Interactive 3D Model**: Allows accurate placement and scaling of the model.
- **GPS-Based AR (Future)**: Option to position models based on GPS coordinates if marker recognition is insufficient.

## 🛠 Technologies Used
- **AR.js**: Core library for augmented reality.
- **A-Frame**: Framework for building 3D/AR scenes.
- **HTML/CSS/JavaScript**: Basic web technologies.

## 🚀 How to Use
1. Open the https://overcloudx.github.io/AR-JS/
2. Grant access to the camera when prompted.
3. Point your camera at the printed marker (e.g., `scan.pdf`) to view the 3D model.
4. Test in various conditions, including outdoor lighting, for stability.

## 📋 Future Plans
- Test the model’s accuracy on-site (±2m precision).
- Evaluate GPS-based AR implementation if marker recognition is unreliable in real-world conditions.

## 📂 Project Structure
```plaintext
.
├── index.html              # Main entry point
├── scan.pdf                # Scan image
├── assets/                 # Assets folder
│   ├── pattern-marker.patt # abandoned AR marker
│   ├── Old_House.glb       # 3D model
│   ├── scan_image.patt     # AR Marker
