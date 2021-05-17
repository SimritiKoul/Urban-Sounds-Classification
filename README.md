# Urban-Sounds-Classification
Executive Summary

Sounds are all around us. Whether directly or indirectly, we are always in contact with audio data. Sounds outline the context of our daily activities, ranging from the conversations we have when interacting with people, the music we listen to, and all the other environmental sounds that we hear on a daily basis such as a car driving past, the patter of rain, or any other kind of background noise. The human brain is continuously processing and understanding this audio data, either consciously or subconsciously, giving us information about the environment around us.
When we input sound in this program, it will automatically classify it into specific categories using Deep Learning techniques: Multi-Layer Perceptron (MLP) and modified Convolutional Neural Networks (CNN). Multi-layer perceptron’s (MLP) are classed as a type of Deep Neural Network as they are composed of more than one layer of perceptrons and use non-linear activation which distinguish them from linear perceptrons. Their architecture consists of an input layer, an output layer and in-between the two layers there is an arbitrary number of hidden layers. Whereas, Convolutional Neural Networks (CNNs) are build upon the architecture of MLPs but with a number of important changes. Firstly, the layers are organized into three dimensions, width, height and depth. Secondly, the nodes in one layer do not necessarily connect to all nodes in the subsequent layer, but often just a sub region of it.
This permits CNN to perform two critical stages. The primary being the highlight extraction stage. Here a channel window slides over the input and extricates the entirety of the convolution at each area which is at that point put away within the highlight outline. A pooling handle is regularly included between CNN layers where regularly the max esteem in each window is taken which diminishes the feature map size but retains the critical information. This can be imperative because it decreases the dimensionality of the network meaning it diminishes both the preparing time and probability of overfitting. At that point in conclusion we have the classification stage. This can be where the 3D information inside the arrangement is straightened into a 1D vector to be yield.
For the reasons examined, both MLPs and CNN’s regularly make great classifiers, where CNN’s in specific perform exceptionally well with picture classification errands due to their include extraction and classification parts. I accept that this will be exceptionally viable at finding designs inside the MFCC’s much like they are compelling at finding designs inside images. 

For complete dataset, please refer Urbansounds8K official website: https://urbansounddataset.weebly.com/urbansound8k.html
