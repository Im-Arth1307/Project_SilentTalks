
# 🤟 Project Silent Talks

This is a dynamic sign language detector. By using TensorFlow, MediaPipe and OpenCV, we're able to train a model to accurately recognize dynamic sign language gestures such as Hello, I Love You and Thanks.

## ⚙️ Features

- Real-time detection of dynamic sign gestures
- Trained using a custom dataset with keypoint extraction
- Uses webcam input for live gesture recognition
- High accuracy


## 🧠 Tech Stack

- Python

- TensorFlow/Keras for gesture classification model

- OpenCV for video capture and visualization

- MediaPipe for hand, pose, and face landmark detection

- NumPy for array manipulation

## 📁 Project Structure
```bash
Project_SilentTalks/
├── Elites Final/                     # Contains initial files for website
├── MP_data/                          # Contains local training data used for initial model training
├── action.h5                         # Trained Keras model for gesture classification 
├── Action_Detection_Utils.py         # Utility functions: drawing landmarks, extracting keypoints, etc.
├── Action Detection Refined.ipynb    # Model training notebook using collected data
├── README.md                         # Project overview and instructions
├── Runner.py                         # Script for running the project
├── Demo.gif                          # GIF of the project in action
└── requirements.txt                  # Required Python libraries

```
## 🚀 Installation and Usage

1. Clone the repository and navigate to it on your machine

```bash
  git clone https://github.com/Im-Arth1307/Project_SilentTalks
  cd Project_SilentTalks
```

2. Install all the necessary dependencies

```
pip install -r requirements.txt
```

3. Run the project
```
python Runner.py
```

4. Press 'Q' on your keyboard to close the sign language detection window
    
## ✨ Demo

_Real-time recognition of "Hello", "ThankYou" and "ILoveYou"_

![Demo of Project SilentTalks in action](Demo.gif)
## 🧠 Future Improvements 

- Add more gestures and words
- Expand the dataset by extracting keypoint data from publicly available sign language videos
- Finish integration and deployment as a web app
## 🤝 Contributing

Contributions are always welcome ! Feel free to fork the repo, make improvements and create a pull request.

## 🙌 Contact
For any questions or suggestions, reach out to:

Atharva Jakhetiya 

Gmail: jakhetiyaathava@gmail.com

LinkedIn: https://www.linkedin.com/in/atharva-jakhetiya/

GitHub: https://github.com/Im-Arth1307
