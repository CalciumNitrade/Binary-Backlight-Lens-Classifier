# Backlight Binary Lens Classifier

This binary classifier uses CNN's to classify lens types which are often used in backlight units of LED/LCD TV's. <br/><br/>
The model consist of 4 Convolution and MaxPooling layers with relu activation followed by 4 dense layers with 2048 neurons each. The model also has 2 Dropout layers with the percentage of 0.2. These layers also use relu activation. The output layer uses sigmoid activation.

The training took about 17 hours. Optimizer used for this project was RMSprop with the learning rate of 0.0001. The lost function used was binary crossentropy. <br/>
