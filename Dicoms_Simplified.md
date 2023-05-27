# Dicom Simplified

Dicom Simplified is an application built with ttkbootstrap that provides a simple interface to visualize, manipulate, and convert DICOM files. It allows you to view DICOM files, adjust the contrast of images, anonymize them, and convert them to PNG, MP4, or NIFTI formats.

<img width="452" alt="image" src="https://github.com/PYCAD-Premium/Dicom-Simplified/assets/37108394/98011292-49a4-431e-ae0b-fa979ad6ad9e">

## Where is the code?
To gain access to this exclusive world of cutting-edge applications, become a Premium Member today. Subscribing to our Premium membership will unlock an ocean of opportunities for innovation and research in medical imaging. To subscribe, follow this link: https://pycad.gumroad.com/l/pycad-premium.

## Features
- Visualize DICOM files: Load a DICOM directory and navigate through the slices.
- Manipulate DICOM files: Adjust the contrast of the images with the min and max sliders.
- Anonymize DICOM files: Protect patient privacy by removing identifying information.
- Convert DICOM files: Convert files to PNG or MP4 formats.
- File information: Get detailed information about a selected DICOM file.

## Installation
To install the application, clone the GitHub repository:

```
git clone https://github.com/PYCAD-Premium/Dicom-Simplified
```

## Dependencies
The application relies on several Python libraries:

- ttkbootstrap
- PIL (Pillow)
- tkinter
- numpy
- pydicom
- glob
- os
- cv2 (OpenCV)

You can install these dependencies using pip:

```
pip install ttkbootstrap Pillow numpy pydicom glob2 opencv-python
```

## Usage
Run the main application script using Python:
```
python app.py
```

## Interface
On launching the application, you will find:

- 'Open': Button to select a DICOM directory.
- 'Visualize': Button to visualize the DICOM slices.
- 'Show info': Button to display information about a DICOM file.
- 'Anonymize': Button to anonymize DICOM files.
- 'Save PNG': Button to save DICOM files as PNG images.
- 'MP4': Button to convert DICOM files to MP4 format.
- Contrast Sliders: Adjust the contrast of the visualized DICOM slice.
- Apply/Change: Button to apply contrast changes or revert them.

## Contributing
Feel free to fork the repository and make changes. If you have any ideas, just open an issue and tell me what you think.

## Contact
If you have any questions, feel free to reach out to the maintainer of this repository.

