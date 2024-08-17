# Handwritten-digit-Recognition

### Web Application
- Flask for web framework
- d3.js for drawing bar graph

## Requirements
- `pip install -r requirements.txt`
- Tested on Python 3.9.13, pytorch 2.0.0, CUDA 11.8

## Usage

- #### Run WebApp
  - `python3 gui_digit_recognizer.py` (then access to `localhost:5000`)
  
- #### Training Model
  - Training on CPU: `train_digit_recognizer.py`
  - Training on GPU: `train_digit_recognizer.py --use_gpu`
