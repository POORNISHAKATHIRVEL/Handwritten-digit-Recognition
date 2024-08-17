# Handwritten-digit-Recognition

### Web Application
- Flask for web framework
- d3.js for drawing bar graph

## Requirements
- `pip install -r requirements.txt`
- Tested on Python 3.9.13, pytorch 2.0.0, CUDA 11.8

## Usage

- #### Run WebApp
  - `python3 server.py` (then access to `localhost:5000`)
  
- #### Training Model
  - Training on CPU: `python3 train.py`
  - Training on GPU: `python3 train.py --use_gpu`
