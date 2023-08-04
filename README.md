
# Automated Supervision with Visual Tracking for Prisoners

The proposed surveillance systems in our research study to
be effective in recognising the actions like Walking, Running and Fighting automatically, both in real time and offline video streaming mode.




## Setup To Do

 - [Download the dataset](https://drive.google.com/drive/folders/1VwZTQ4AylTRa6JCv7mHByGT87ICo1Bn-?usp=sharing)
 - [Download YOLO Model weights](https://drive.google.com/file/d/1APwXTM2TMW81xswlU6l4Z9ly9Zi75bdp/view?usp=sharing)
 - Add the dataset and weights in proper location


## Folder Structure

Arrange the downloaded folder in the same way as shown below

```bash
|-DLVC_project
  |-Dataset
    |-Fighting
    |-Walking
    |-Running
  |-Predict
  |-yolo-coco-data
    |-coco.names
    |-yolov3.cfg
    |-yolov3.weights
  |-Model_creation.ipynb
  |-prediction.ipynb  

```


## Installation

Install all the required libraries using pip

```bash
  cv2
  pafy
  numpy
  tensorflow
  matplotlib
```

## Run .ipynb file 

Run .ipynb file using jupyter notebook

```bash
  jupyter notebook Model_creation.ipynb
  
  jupyter notebook prediction.ipynb
```  
    
## Result

After running .ipynb files, you will get

- weights of our model(which will be used for prediction)
- All the graph to analyze the model

