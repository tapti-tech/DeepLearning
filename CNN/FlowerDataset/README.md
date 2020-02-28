Dataset  - https://www.kaggle.com/alxmamaev/flowers-recognition

Used Keras Pretrained Resnet Model

Following steps performed:

1. Data Preparation: 
        a) All images were made of the same resolution.
        b) Placed the images in two different folders - 'rose' and 'daisy' to train .
2. Data Pre-processing: Morphological Operations
        a) Applied thresholding on the image - convert from a grey image to binary image.
        b) Applied techniques Erosion, Dilation, Opening, Closing.
3. Data Pre-processing: Normalisation
        a) Applied and check various techniques of normalisation and its affect on images.
        
4. Data Pre-Processing: Augmentation
         a) Applied data augmentation techniques ie(Linear Transformation, Affine Transformation, Scale Transformation, Shear Transformation, Bright Jitter).
         b) Different ways to augment - translation, rotation, scaling, etc.
5. Model Building using CNN ResNet Architecture (Transfer Learning)
         a) Running ablation experiments
         b) Overfitting on a smaller version of the training set
6. Hyperparameter tuning
7. Mode training and evaluation
 
