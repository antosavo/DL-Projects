
The aim of this project is to detect stars in the image "Pleiades_Star_Cluster.jpg" using a deep neural network:

•  The script "1_Image_Augmentation.ipynb" uses image augmentation to create new images from sample images of stars and "empty space". This step is necessary because to train a deep neural network we need at least 1000 images.

•  The script "2_Train_A_Deep_Learning_Model_For_Image_Classification.ipynb" trains a convolutional neural network (CNN) to classify images of stars and "empty space". The trained model is saved in the file DL_model.h5.

•  The script "3_Object_Detection.ipynb" detect stars in the image "Pleiades_Star_Cluster.jpg" using the previously trained model DL_model.h5.

If for some reason you can't see an ipynb file, copy its URL into:

https://nbviewer.jupyter.org