# SignVision (SLR for 3 classes currently)

POC which detects and recognizes sign language gestures using mediapipe keypoints and a tensorflow based lstm model. GUI is built using tkinter.
Currently done for 3 classes:
- Hello
- Thank you
- I love you

## Installation

1) Clone the repository
```bash
git clone 
```

2) Install the required libraries within the virtual environment
```bash
pip install -r requirements.txt
```

3) Run the main.py file
```bash
python app.py
```

4) Visualize logs using tensorboard
```bash
tensorboard --logdir=Logs/
```

5) To train the model, use the `training.ipynb` notebook