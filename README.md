# RealTime_DigitRecognizer
A real time digit recognizer using machine learning and OpenCV

First we need to train the model in ```RealTimeDRTraining.ipynb```.

We required the dataset for training which is ```Data.zip``` extract it in the same folder where you have all the files.

And Train the model.

But if you dont want to train and directly test,the model is still provided to be used directly.

To test the model use ```RealTimeDigitRecognition.ipynb```

First we will create a normal real time detection without bounded boxes

![output2](https://user-images.githubusercontent.com/42001739/82623233-47b07800-9bfd-11ea-9c97-ebe53a8d4a09.PNG)


Then we will add bounded boxes and ouput will be as shown below.

![rt1](https://user-images.githubusercontent.com/42001739/82623109-061fcd00-9bfd-11ea-9879-eb3437e5b5f3.png)

## Changes Required:
- Bounded Boxes accuracy needs to be increased
