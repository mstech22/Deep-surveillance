# Deep-surveillance


In this video surveillance project, I have introduced a spatio temporal autoencoder, which is 
based on a 3D convolution network. The encoder part extracts the spatial and temporal 
information, and then the decoder reconstructs the frames. The abnormal events are identified by 
computing the reconstruction loss using Euclidean distance between original and reconstructed 
batch.
In this project basically, I choose a video file and then the model will find the abnormal events 
or activities like fighting, stealing, etc. 
My project have two main components, one is a deep neural network model and another is its 
frontend
