
# Handwritten Doctor notes Recognition Web App
 link : https:/https://yochi2545.github.io/MorYa/
<br>
<h3>Structure of App</h3>
<h2> keras - > Tensorflow.js ->(html + css + javascript)->github pages</h1>
  <h3>Hello World of Object Recognition!</h3>
 <h2>Aim:</h2> To make a convolution neural network to recognise handwritten Doctor notes Recognition.
 <br>
 <h2>labeled_classmedicine DATASET:</h2>The training dataset contain 500 images and testing contain 10000 images .Each image is  resize to 256x256 pixel and grey scale.
  <br>
 <h2>CNN MODEL OVERVIEW:</h2>
 <br>⚈ It is a 17 layer model with Conv2D,MaxPooling2D,BatchNormalization,Dense,Flatten and Dropout layer combination.
 <br>⚈ 32 epochs are used.
 <br>⚈ Categorical_loss is loss function and adam is used for optimization.
 <br>⚈ Model gives  91.33333563804626 accuracy.
<h2>For Deployment:</h2>Save model using tensorflowjs converters as json file and weight as .h5 file.Use Tensorflow.js to load model and predict in javascript file

