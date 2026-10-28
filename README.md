# AR Cadaver Visualization

## Overview
AR Cadaver Visualization is an Augmented Reality (AR) application that allows users to explore a 3D human anatomical model in a real-world environment using an Android smartphone. The application uses the phone's camera to detect horizontal surfaces, such as tables or floors, and allows users to place and view a 3D human model directly in the physical environment.

The project aims to make anatomy learning more interactive, immersive, and accessible by combining Augmented Reality with 3D anatomical visualization.

## Features
- **Markerless AR:** Detects real-world surfaces without requiring printed markers.
- **Surface Detection:** Identifies suitable surfaces using the device's AR capabilities.
- **3D Human Model:** Displays a human anatomical model in the real environment.
- **Interactive Placement:** Allows users to tap the screen to place the model on a detected surface.
- **Real-World Scale:** Adjusts the model to an appropriate size for anatomical study.
- **Mobile Accessibility:** Designed to run on compatible Android devices.

## Technologies Used
- HTML
- JavaScript
- Three.js
- WebXR Device API
- GLTFLoader
- GLB 3D model format
- GitHub Pages for hosting

## How It Works
1. The user opens the application in a compatible Android browser.
2. The camera starts an Augmented Reality session.
3. The application detects horizontal surfaces in the surrounding environment.
4. A placement indicator shows where the 3D model can be positioned.
5. The user taps the screen to place the human anatomical model.
6. The model appears anchored to the detected surface for visualization.

## Project Structure
```text
AR-Cadaver/
├── index.html
├── models/
│   └── cadaver.glb
└── README.md
```

## Setup and Usage
1. Clone or download this repository.
2. Ensure the 3D model is available at `models/cadaver.glb`.
3. Host the project using HTTPS, for example, through GitHub Pages.
4. Open the hosted webpage on a compatible Android device using Chrome.
5. Allow camera access and follow the on-screen instructions to place the model.

## Requirements
- An Android smartphone compatible with WebXR immersive AR.
- A supported browser, such as a compatible version of Google Chrome.
- Camera permission.
- A secure HTTPS connection.
- A valid GLB-format 3D anatomical model.

## Future Enhancements
- Add a detailed standing human anatomical model with internal organs.
- Support individual organ selection and highlighting.
- Add labels and descriptions for anatomical structures.
- Enable model rotation, scaling, and repositioning.
- Include separate views of the skeletal, muscular, circulatory, and digestive systems.
- Add educational information for medical and anatomy students.

## Purpose
The project explores how markerless Augmented Reality can support anatomy education by allowing learners to visualize three-dimensional human anatomy in a real-world setting.

## License
The project's source code and 3D assets may have different licenses. Check the license of each asset before redistributing it.
