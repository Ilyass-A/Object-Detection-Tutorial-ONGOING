# Object Detection Tutorial (Ongoing)
### About
I am currently studying to build an Object Detection Model.
### Setup and Installation
It is necessary to execute these steps in order to run the code. I used cmd to execute the following steps:
1. Creation of a virtual enviroment:  
`python -m venv your_environment_name`
2. Activation of the virtual environment:  
`.\environment_name\Scripts\activate`  
3. Upgrade pip:  
`python -m pip install --upgrade pip`
4. Installation of ipykernel:   
`pip install ipykernel`
5. Installation of the virtual environment to jupyter Notebook:  
`python -m ipykernel install --user --name=obdec`

### Training and Detection of the Model  
- Pretrained Models: [Tensorflow Model Zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md "Tensorflow Model Zoo") (Pre- and postprocessing are automatically done)
- Model selction depends characterized by:
  - high accuracy = slow detections
  - fast detections = low accuracy
