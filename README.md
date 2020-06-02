# Facial-Expression-Recognition

This project leverages the power of Tensorflow & Keras to recognize facial expression of the person(s) in videos and images or through
web camera. 
The dataset available in this repository consists of 7 different categories of facial expression in grayscale format.
The different categories are : "Angry", "Disgust", "Fear", "Happy", "Neutral", "Sad" & "Surprise".

Setup instructions:
1. Clone the repository or download it.

2. The easiest way to install most of the dependencies is to first install Anaconda, which makes sure that all necessary libraries  & Python 
   is readily available.
   
3. Or you can try to install all these by typing "pip install -r requirements.txt" by moving into  the project directory.

4. You need to install Tensorflow >=2.0.1 (recommended) and Python < 3.8

5. After the installation is complete, run the development server using the command "python main.py", and you can preview it in your browser.

NOTE:
1. In camera.py file : line 12, the default video path is your computer's web camera. There are two videos in the project folder which you 
   can use to see the results by setting the path to those videos.
  
2. The server will start at http://0.0.0.0:5000/
   If the site doesn't opens in the browser set "debug = False" in main.py : line 27
   Now, the site will be accessible at http://127.0.0.1:5000/
