
# Handwritten Doctor notes Recognition Web App
 link source code and dataset : https://drive.google.com/drive/folders/1XyeTH7-3uAJS037UoIDvYKj3TNVx7DpV
 link : https:/https://yochi2545.github.io/MorYa/
<br>
<h3>Doctor Handwritten</h3>
<h2> keras - > Tensorflow.js ->(html + css + javascript)->github pages</h1>
  <h3>Hello World of Object Recognition!</h3>
</h2> To make a convolution neural network to recognise handwritten Doctor notes Recognition.
 <br>
 <h2>labeled_classmedicine dataset:</h2>The training dataset contain 350 images and testing contain 150 images .Each image is  resize to 256x256 pixel and grey scale.
<h2>Project & Process Overview:</h2>
<br>⚈ Data Collection:
Gather handwritten samples of the 5 class 5 medicines in painkiller you mentioned: Cemol, Panadol, Paracap, Paracetamol, Tylenol. 
<br>⚈Data Preprocessing:
Preprocess the images to make them suitable for training. This may include resizing, normalization, and converting to grayscale.
<br>⚈Model Training and Detail:
batchsize 64 epoch 32 are used. categorical_loss is loss function.
Model gives  91.33333563804626 accuracy.
Utilize VGG19 as a feature extractor or as a pre-trained model for feature extraction.
Build and train a neural network (e.g., CNN) on top of VGG19 to classify the handwritten medicines.
<br>⚈Model Evaluation:
Evaluate the trained model's performance using metrics like accuracy, precision, recall, and F1-score.
<h2>For Deployment:</h2>⚈Save model using tensorflowjs converters as json file and weight as .h5 file.Use Tensorflow.js to load model and predict in javascript file

<br>Data preprocessing: Tamfa
<br>Train model: Aunchalee & Wittawit
<br>Deploy: Wittawit
