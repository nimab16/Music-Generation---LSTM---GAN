# Music-Generation-LSTM-GAN

use the **GAN** and **LSTM** to create new music. I used three sources to produce the
musics. Two of them are based on the LSTM and one of them is based on GAN. The LSTM Unlike standard
feedforward neural networks, LSTM has feedback connections. It can process not only single data points (such
as images), but also entire sequences of data (such as speech, video or music). 

For the first try with **Keras
Music Generation**, it makes sequential model with several layers and uses LSTM as it time dependent data.
The second one is **Classical-Piano-Composer** that is based on LSTM and different layers from the first try
and also different dropout. In addition this source has a pretrained model that can be used to generate music.
The third one is the GAN part to generate a music according to dataset that contain 307 Pokemon musics.

# Classical-Piano-Composer with LSTM
This model in terms of training contains 4 hidden layers and 3 different dropout between layers. Also, it has
Activation Relu and Softmax. The optimizer is rmsprop. The dataset contains 92 clasical piano music that is
quite good for training.
I tried to train my model just for 20 epochs it takes 3 hours even I used
the GPU of Colab. Also, you can use the pretrained model that was called **Weights.hdf5** and the Prediction class. The
dataset is contain 92 classical piano music.


# Requirements for Keras Music Generation
I used the below libraries in **Google Colab:**

```
tensorflow==1.14.0
tensorflow-gpu==1.14.0
mido==1.2.9
Keras==2.1.2
sklearn==0.0
numpy==1.17.3
```
Thanks from https://github.com/subpath/Keras_music_gereration


