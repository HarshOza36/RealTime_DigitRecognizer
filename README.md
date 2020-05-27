# RealTime_DigitRecognizer
A real time digit recognizer using machine learning and OpenCV

We will first create single digit rercognition in ```RealTimeDigitRecognition.ipynb``` and then multidigit recognition in ```RealTimeMultiDigitRecognition.ipynb```

# Final output in ```RealTimeMultiDigitRecognition.ipynb``` will be

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/42001739/82968228-71e1ab80-9fea-11ea-8c55-53d5cdcc97d8.gif">
</p>




First we need to train the model in ```RealTimeDRTraining.ipynb```.

We required the dataset for training which is ```Data.zip``` extract it in the same folder where you have all the files.

And Train the model.

But if you dont want to train and directly test,the model is still provided to be used directly.

To test the model use ```RealTimeDigitRecognition.ipynb```

First we will create a normal real time detection without bounded boxes

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/42001739/82623233-47b07800-9bfd-11ea-9c97-ebe53a8d4a09.PNG">
</p>

Then we will add bounded boxes and ouput will be as shown below.

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/42001739/82623109-061fcd00-9bfd-11ea-9879-eb3437e5b5f3.png">
</p>

## Changes Required:
~~- Bounded Boxes accuracy needs to be increased~~

## All changes updated and created MultiDigit Recognition ipynb file
