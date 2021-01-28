About the notebook test_DS2.ipynb

I used the CIFAR10-CNN model with just one minor change. I changed the optimizer
from RMSprop to Adam. This change was done simply because in my personal
experience Adam works better than RMSprop.

My computer was crashing frequently possibly due to the heavy calculations. For
this reason I was forced to use only 10000 images and not the whole database
to train my network. Despite of that, I believe that the trained model performed
well, since the validation-set accuracy was higher than 90% (as was training-set
accuracy).

In my computer I was not able to save the corrected figures of the whole test
set (I am still not sure why, but my computer was crashing every time). For this
reason I selected 500 images from the test set and corrected them. Those figures
are in the zip file 'corrected_images.zip'.
