* I have used fashion MNIST dataset containing 70,000 images belonging to 9 class labels namely:-
  * 0: T-shirt/top
  * 1: Trouser
  * 2: Pullover
  * 3: Dress
  * 4: Coat
  * 5: Sandal
  * 6: Shirt
  * 7: Sneaker
  * 8: Bag
  * 9: Ankle boot
* Then I have split the data into training and test set with 80:20 ratio.
* This is followed by data augmentation by performing the following operations:
   * Rotation
   * Width shift
   * Height shift
   * Shearing
   * Zoom
   * Horizontal flip
* After this the data is used to train 2 SVM classifiers with the following hyperparameters:
   * Model 1:
       * Kernel=linear
       * C=0.1
   * Model 2:
        * kernel=linear
        * c=0.1
        * gamma=0.01
* The performance of the model is evaluated using the following metrics:
   * Accuracy
   * Precision
   * Recall
   * F1 score 
* Following this I generated a classification report and confusion matrix showing the performance of the model.
