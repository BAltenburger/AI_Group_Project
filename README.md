# AI_Group_Project

## Startup:

Make a virtual environment & pip install the requirements.txt
The ipynb should then run on its own. 
If you are training, run all cells & make sure to set a new save file for the model.
If you just want to evaluate model performance and have a trained model in the models folder, run cells starting after the model is loaded in using the correct model file.
Here are some comments from the training section of the code:

```
#Currently I just load the model trained on imagenet and train the whole thing
#I should probably set learning rate an order of magnitude lower in the future
#(I just wanted this to run fast enough to test)

#Training things to do:
#Set lr to 0.0001

#1
#Rerun this model where we do transfer learning and train everything together immediately

#2
#Do the same but load the same model without any of the pretrained weights
#(change weights argument in previous cell)

#3
#Freeze the efficientnet model and train only the layers I added 

#4
#Freeze the efficientnet model and train only the layers I added
#But then unfreeze and use a much smaller (10 - 100x) lr to fine tune the whole thing

#See - https://keras.io/guides/transfer_learning

#Other things to do:
#Make nice looking plots illustrating performance throughout training for various models
#Probably confusion matrices or accuracy type stats for different models
#Plot some example images from the data set
#These are all done in naive and primitive forms below
```


Test push -Sophie