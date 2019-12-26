# Dog_Breed_classifier

This model predict the Breed of the dog given a image from the below sets.

1.pug
2.Bull dog
3.Labrador Reterviver
4.Beale
5.pomeranian
6.German shephard

Data collection:
           we must run some Javascript code in our browser which will save the URLs of all the images you want for our dataset. First, go to Google Images and search for the images we want per class. Once we're on the results page, press CtrlShiftJ in Windows/Linux and CmdOptJ in Mac, and a small window the javascript 'Console' will appear. That is where you will paste the JavaScript commands.

we will need to get the urls of each of the images. Before running the following commands, we may want to disable ad blocking extensions (uBlock, AdBlockPlus etc.) in Chrome. Otherwise the window.open() command doesn't work. Then you can run the following commands:
                  For creating the dataset please refer the Data_set_download.ipynb
                  
Model :         Used CNN Transfer Learning Resnet to train the model with 5 epochs.
                later finetune the model by finding the appropriate learning rate with 8 epochs.
                Saved the model in the .pkl format for deploying in any web interface or to predict the breed of the dog.
                
   
Note: Due to size limit i didnt uploaded the images folder and export.pkl (model) in github instead please uncomment the two fields
        (#downloading the images and '''import pickle ) and run the dogBreedclassifier.ipynb so that a new set of images will be 
        downloaded and will get trained.
                

Please feel free to provide a feedback for the below mail id : santhoshbfun@gmail.com
