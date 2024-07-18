<div align="center">
    <img width="745" alt="DICOM Viewer" src="https://github.com/user-attachments/assets/27c74466-6d2a-4c2d-8bef-c29b020a3bb2">
</div>

# DICOM Viewer with Volume Rendering

## Overview
This project is a DICOM viewer with volume rendering capabilities, implemented using VTK (Visualization Toolkit) and pyQt. The application allows users to load DICOM files, choose between surface rendering and ray casting rendering, and adjust parameters such as iso value for surface rendering and shading properties for ray casting rendering.

## Features

### 1. Loading DICOM Files
- Click the "Load" button to open a file dialog and select a DICOM series folder.
- The application uses the vtkDICOMImageReader to load DICOM series data.

### 2. Surface Rendering
- Choose the "Surface Rendering" radio button.
- Adjust the iso value using the iso slider to control the appearance of the rendered surface.
- Real-time rendering updates are available with the "Real-Time Rendering" checkbox.

### 3. Ray Casting Rendering
- Choose the "Ray Casting Rendering" radio button.
- Adjust ambient, diffuse, and specular properties using sliders.
- Real-time rendering updates are available with the "Real-Time Rendering" checkbox.

## User Interface
- The UI is designed using PyQt5, providing an intuitive and user-friendly environment.

## Demo


https://github.com/MohamedMandour10/GFX-DICOM-Viewer/assets/115044826/7f3e9a03-e435-4fa3-941c-2f98018bff4b


 
## How to Use

1. Launch the application.
2. Click the "Load" button to select a DICOM series folder.
3. Choose the rendering technique using the radio buttons.
4. Adjust parameters such as iso value or shading properties based on the selected rendering method.
5. Enable "Real-Time Rendering" for dynamic updates.
6. Explore the rendered volume using the interactive UI.


## How to Run

1. Install the required dependencies using 
```bash
pip install -r requirements.txt
```
2. Run the application using 
```bash
python app.py
```
