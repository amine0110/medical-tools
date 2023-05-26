# Medical Annotation For Yolo

This repository contains code for our tool that converts medical annotations into YOLO-v5-v8 format. The tool is designed for easy use and has a simple interface, which makes the process of annotation conversion as easy as a single command.

NOTE: This repository is part of the PYCAD Premium program. To access the code, you must be a paid GitHub member.

<img width="547" alt="image" src="https://github.com/PYCAD-Premium/Medical-Annotation-For-Yolo/assets/37108394/4e836b82-f4dc-4460-9eac-c7cdf08a1fa7">


## Usage
1. Clone this repository to your local machine:
```
git clone https://github.com/PYCAD-Premium/Medical-Annotation-For-Yolo.git
```

2. Navigate into the cloned repository:
```
cd Medical-Annotation-For-Yolo
```

3. Install the necessary requirements:
```
pip install -r requirements.txt
```

4. Use the tool by executing the main script:
```
python app.py
```

This script will convert all annotations in the 'input_folder' into YOLO-v5-v8 format and will save the results in the 'input_folder'.

## How it works
The tool works by parsing annotation files in the 'input_folder', converting each annotation into YOLOv5 format, and writing the converted annotations to the 'output_folder'. The specifics of this process depend on the format of the input annotations and the options passed to the tool.

## Contributing
We appreciate all contributions. If you are planning to contribute back bug-fixes, please do so without any further discussion.

If you plan to contribute new features, utility functions, or extensions, please first open an issue and discuss the feature with us.

## Contact
If you have any questions, comments, or issues, please don't hesitate to contact us. Here's our [email](mailto:mohammed@pycad.co).

