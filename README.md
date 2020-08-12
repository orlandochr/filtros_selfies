# filtros_selfies
Proyecto de Machine Learning - Manejo de imágenes con openCV

El proyecto contiene
Jupyter notebook 
  proyectoFiltros.ipynb

Modelo entrenado :
  Tensor flow model1.h5

carpeta de imagenes
/images

capeta de modelo
/model2
  haarcascade_eye.xml
  haarcascade_frontalface_default.xml
Dataset training y test
  test.csv (no incluidos en el repositorio)
  training.csv  (no incluidos en el repositorio)
  

##Crèditos:

Data sets keypoints 
kaggle.com
Facial Keypoints Detection
Detect the location of keypoints on face images
https://www.kaggle.com/c/facial-keypoints-detection/data

##Data files

training.csv: list of training 7049 images. Each row contains the (x,y) coordinates for 15 keypoints, and image data as row-ordered list of pixels.
test.csv: list of 1783 test images. Each row contains ImageId and image data as row-ordered list of pixels

##Haarcascades
Para identificación de los Keypoints
opencv/opencv
https://github.com/opencv/opencv/tree/master/data/haarcascades
  haarcascade_frontalface_default.xml
  haarcascade_eye.xml


