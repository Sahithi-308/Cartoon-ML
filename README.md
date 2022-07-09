# Cartooning an Image-ML

## Installation

### Application tested on:

- python 3.7
- tensorflow 2.1.0 
- tf_slim 1.1.0
- ffmpeg 3.4.8
- Cuda version 10.1
- OS: Linux (Ubuntu 18.04)


### Using `virtualenv`

1. Make a virtual environment using `virutalenv` and activate it
```
virtualenv -p python3 cartoonize
source cartoonize/bin/activate
```
2. Install python dependencies
```
pip install -r requirements.txt
```
3. Run the webapp. Be sure to set the appropriate values in `config.yaml` file before running the application.
```
python app.py
```
## Output:
![1](https://user-images.githubusercontent.com/85608117/178100361-8a3d3011-e277-42fa-b96f-d241bfe5c518.png)
![2](https://user-images.githubusercontent.com/85608117/178100371-9b7cd283-2b9f-4090-b70f-e5d9ba20410e.png)
