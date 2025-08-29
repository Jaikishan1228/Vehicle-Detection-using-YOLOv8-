# YOLOv8 Vehicle Detection

This project trains and tests a YOLOv8 model for vehicle detection using a custom dataset. It includes:
- Training on images and labels in `Vehicle_Detection_Image_Dataset/`
- Testing on images and video
- Saving results to the `runs/` folder

## Usage
- Edit and run `main.ipynb` for training, testing, and video detection
- Results are saved in `runs/`

## Requirements
- Python 3.8+
- Ultralytics YOLOv8
- OpenCV
- PyTorch

## Quick Start
1. Clone this repo
2. Install dependencies: `pip install ultralytics opencv-python torch`
3. Run `main.ipynb` in Jupyter or VS Code

## Project Structure
```
Vehicle_Detection_Image_Dataset/   # Custom dataset
main.ipynb                        # Notebook for training/testing
runs/                             # Output results
models/                           # Pretrained models
```

## Example Results
- Detected vehicles in images and video
- Annotated output saved in `runs/`

## License
MIT
