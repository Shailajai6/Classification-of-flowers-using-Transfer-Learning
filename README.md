# Classification-of-flowers-using-Transfer-Learning
Trained the model using transfer learning to classify the different classes in jena flower dataset.Done preprocessing to preprocess the data in to training and validation and created folders for different classes in the dataset. Created paths to access the images from the corresponding folders. Augmented data using the image generator and used for training the model.
# Analysis
  - Used different  padding techniques  'same' and 'valid' to train the model and cntrol the shape of the output.Used  batch Normalization technique for identitical data distributions. Activation function used is Relu and as it is the multi class classification used softmax activation function.

 - Accuary obtained in the model  for the test images is 96 percent,recall is 95 percent.
- Initially the validation loss was high but then it has reduced and smoothened.
