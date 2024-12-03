# CS 405 - Project 2: WebGL 3D Visualization

## Introduction

This WebGL-based application is developed as part of the coursework for CS 405. It is designed to demonstrate advanced features of WebGL, including 3D rendering, texture mapping, lighting effects, and interactive controls. The application allows users to load and visualize 3D models in the `.obj` format, apply multiple textures, and manipulate lighting settings to observe the impact on the rendered object.

## Features

- **3D Model Visualization**: Render 3D models from `.obj` files directly in the browser.
- **Multiple Textures**: Supports loading and blending of two different textures onto the 3D model.
- **Dynamic Lighting**: Implement ambient and specular lighting that can be adjusted in real-time through user interface controls.
- **Interactive Controls**: UI components allow dynamic interaction with the 3D model, such as rotation, texture blending, and lighting adjustments.

## Installation

No installation is necessary. You can run the project directly from a local server due to browser security restrictions related to file paths.

### Running the Project

To run the project on your local machine:

1. **Clone or Download the Repository**

   If you have git installed, clone the repository using:
  https://github.com/cgb47/cs405Project2
  https://github.com/cgb47/cs405Project2.git
  

Alternatively, you can download the project as a ZIP file and extract it.

2. **Start a Local Server**

Navigate to the project directory in a terminal or command prompt. Use one of the following methods to start a local server:

- **Python 3.x:**
  ```
  python -m http.server
  ```
- **Node.js with http-server:**
  ```
  npm install -g http-server
  http-server
  ```

3. **Access the Application**

Open a web browser and go to `http://localhost:8000`. Adjust the port number based on the output from your server command if different.

## Usage

- **Loading a 3D Model**: Click the "OBJ model" button to choose and upload a `.obj` file.
- **Applying Textures**: Use the "Texture image" inputs to select and apply up to two textures. Adjust the blending slider to see effects of texture blending.
- **Lighting Controls**: Use the provided sliders to adjust the ambient and specular lighting intensities.
- **Rotation Controls**: Enable auto-rotation or manually adjust the rotation speed to see different angles of the 3D model.



## Contact

For questions and feedback, please reach out to the repository owner or open an issue in the GitHub repository.
