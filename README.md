# Introduction
use the GAN and LSTM to create new music. I used three sources to produce the
music. two of them are based on the LSTM and one of them is based on GAN. The LSTM Unlike standard
feedforward neural networks, LSTM has feedback connections. It can process not only single data points (such
as images), but also entire sequences of data (such as speech, video or music). For the first try with Keras
Music Generation, it makes sequential model with several layers and uses LSTM as it time dependent data.
The second one is Classical-Piano-Composer that is based on LSTM and different layers from the first try
and also different dropout. In addition this source has a pretrained model that can be used to generate music.
The third one is MIDI File LSTM and GAN that I used the GAN part to generate a music according to
dataset that contain 307 Pokemon music.
