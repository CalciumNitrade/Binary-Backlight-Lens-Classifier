# Backlight Binary Lens Classifier

This binary classifier uses CNN's to classify lens types which are often used in backlight units of LED/LCD TV's. These are refractive and reflective type lenses. <br/><br/>
The model consist of 4 Convolution and MaxPooling layers with relu activation followed by 4 dense layers with 2048 neurons each. Model also has 2 Dropout layers with the percentage of 0.2. These layers also use relu activation. The output layer uses sigmoid activation.

The training took about 17 hours. Optimizer used for this project was RMSprop with the learning rate of 0.0001. The lost function used was binary crossentropy. <br/>

Used 2600 photos for training and 340 photos for validation.

The accuray on the validation set is 89%.

![Alt Text](https://github.com/CalciumNitrade/Backlight-Lens-Classifier/blob/main/train.png)
![Alt Text](https://github.com/CalciumNitrade/Backlight-Lens-Classifier/blob/main/validat.png)

Due restrictions, I am not able to share the train and validation data but I added some test samples to the folder.
