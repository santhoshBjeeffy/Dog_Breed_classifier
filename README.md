# Dog_Breed_classifier

This model predict the Breed of the dog given a image from the below sets.

1.pug
2.Bull dog
3.Labrador Reterviver
4.Beale
5.pomeranian
6.German shephard

Data collection: The above images has been scraped from the google search engine i.e at a time 200 images link will be 
                  generated and will be downloaded and saved in the drive.
                  
Model :         Used CNN Transfer Learning Resnet to train the model with 5 epochs.
                later finetune the model by finding the appropriate learning rate with 8 epochs.
                Saved the model in the .pkl format for deploying in any web interface or to predict the breed of the dog.
                
   
Note: Due to size limit i didnt uploaded the images folder and export.pkl (model) in github instead please uncomment the two fields
        (#downloading the images and '''import pickle ) and run the dogBreedclassifier.ipynb so that a new set of images will be 
        downloaded and will get trained.
                
