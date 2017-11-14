# Real-time Emotion Recognition using Deep Learning

- Affective Computing Course
- Prof. Dra. Paula Dornhofer Paro Costa
- FEEC Unicamp

# Authors

- Diego Cardoso Alves
- Murilo Marin Pechoto

# Dependencies

You will need Python 3.5 or higher and some libraries. The easiest way to install these libraries is to install it as part of the Anaconda distribution.

1. Install Python 3, available in: https://www.python.org/downloads/

2. If PIP is not installed, please install: https://pip.pypa.io/en/stable/installing/

3. Install Dlib using conda: conda install -c conda-forge dlib=19.4

4. Dowload OpenCV from here (https://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv) ou try "pip install opencv-python"

5. Install all libraries required using Anaconda such as Pandas, scikit-learn, Keras, etc.

6. Request the CK+ dataset: http://www.consortium.ri.cmu.edu/ckagree/ . After approved, separate the folders source_emotion, source_images and landmarks to use with CK+ Emotion notebook.

7. Download FER2013 dataset: https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

P.S: Some problems could be solved following this question on stackoverflow: https://stackoverflow.com/questions/43184887/dll-load-failed-error-when-importing-cv2

# How to run the code

1. Clone this repo into your environment

2. Open command terminal and cd to root folder:
> cd []\facialrecognition

3. Run command script:
> jupyter notebook

4. Run the notebook according to the model chosen for analysis