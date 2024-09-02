# Circle Crop Tool

A simple graphical application for cropping images into circular shapes using Python. This tool allows users to load an image, draw a circle over it, and save the cropped image in the desired circular shape. The application is built using `tkinter` for the graphical user interface and `Pillow` (PIL) for image processing.

![ScreenShot](https://github.com/user-attachments/assets/f3fb6f4c-71ea-4996-923a-2c5eecaf08ee)


## Features

- **Load Images**: Choose image files in `.jpg` or `.png` formats.
- **Draw and Move Circles**: Draw a circle on the image and adjust its position.
- **Save Cropped Image**: Save the part of the image within the circle as a new PNG file.
- **Custom Icon**: Optionally set a custom icon for the application window.

## Installation

### Prerequisites

Ensure you have Python installed on your system. You will also need to install the following Python libraries:

- `tkinter` (usually included with Python)
- `Pillow` (Python Imaging Library)

To install `Pillow`, run:

```bash
pip install pillow
```
## Running the Application

### Clone the Repository


git clone [https://github.com/yourusername/circle-crop-tool.git](https://github.com/javelinsoft/circle-cropping-tool)
cd circle-crop-tool

## Run the Script
Run the application using Python:

```bash
python ImageCrop.py
```
## Usage

    Load Image: Click the "Load Image" button to select an image file from your computer.
    Draw Circle: Click and drag to draw a circle on the image. Adjust the circle's size by dragging the mouse.
    Move Circle: Click inside the circle and drag to move it.
    Save Image: Click the "Save Image" button to save the cropped image. The image will be saved in the circular area defined by the circle.

## Packaging

To distribute the application as a standalone executable, use PyInstaller. Follow these steps:
Install PyInstaller


pip install pyinstaller

## Package the Application

Use the following command to create a single executable file. Replace icon.ico with your icon file if you have one, and crop.py with the name of your Python script:

```bash
pyinstaller --onefile --icon=icon.ico ImageCrop.py --windowed
```
This will create an executable in the dist directory.

### Contributing

Feel free to open issues or submit pull requests if you have improvements or suggestions. Your contributions are welcome!

