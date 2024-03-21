This current repository contain the jupiter note file which is downloaded from the google colab 
and the dataset is created from the provided link for the app. first of all take the screen shorts of the targated categories and make folder for them respectively as well as 
done croppin for the images as during screenshort the extra area is not usefull.
then the zip file is created for the dataset foldar and uploaded on google drive in order to get ride from the multiple uplodation on the google colab.
The images convert into numpy arrays in order to to fast the traing process if i do traing with the images then it will required much more time.                                          
the maganed the data according to the requirments and only five categories is collected at the moment because some of them is missing and apply augmentation technique to
get the product chracteristic with different angles and sides.
then split the dateset into three part in which 80% data is keep for the training purpose and rest one divide into validate and testing purpose.
after training the model with sequential layers then used the earlystoping method in order to reduced the computation power.
and also try the transfer learning technique in order to check its impact with already trained model. 
Result refect thats the model is unstable throughout the training it may be happend due to the class imbalanced or something else . i was try the reduced its unstability in order 
to changed its parameter and changing the layers and learning rate as well and this result is the best outcome throughout the procedure and i know its not the best one and 
it would be improved time to time.

