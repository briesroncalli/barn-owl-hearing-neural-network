# Studying Barn Owl Ears with a Neural Network
#### *Ben Ries-Roncalli*

The goal of this project is to mimic a barn owl ear using a neural network trained on features of sound data and study how it performs on data with varying levels of noise introduced. 

The data (`input_features.csv`) is generated using Head-related transfer functions, which simulate the sounds that would be received at the left and right ears of a barn owl for sounds presented from different directions in space. The true direction of the sound is measured by the azimuth and elevation in degrees from the barn owl, which are the last two columns in the table, respectively. This particular data was generated from -90 degrees to 90 degrees with step size 5 degrees for both azimuth and elevation.

By training a neural network on the features of this sound data, we are able to predict the azimuth and elevation of the origin of the sound, as a barn owl might. By introducing varying degrees of random Poisson noise to the data, we can examine how resistant this network is to noise and how networks trained on noisy sound data perform.

Last edit: 11/15/2022