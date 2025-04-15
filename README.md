# Image-Captioning-with-Hybrid-Model-with-speech-output
It involves generating textual descriptions of images and converting them into speech using a combination of deep learning models for feature extraction and classification.
Image captioning, the activity of generating textual descriptions for images, is a difficult challenge that 
lies at the intersection of vision and language understanding. Previous solutions of this problem have 
primarily focused on using CNNs for extracting features from the image and using RNNs for sequential 
text generation. From the CNN architectures, ResNet50 has been one of the architectures that have been 
hailed for deep hierarchical feature extraction, which is used by the architecture to learn details within 
images. On the other hand, MobileNet is said to be lightweight and hence very suitable for deployment 
in systems that have limited computational power. If one uses only ResNet50 or only MobileNet, it is 
possible they would not fully utilize the representational power and at the same time efficiency that can 
be gotten from the integration of the two architectures. 
Here, we design a new model with ResNet50 and MobileNet to take the advantages of both architectures 
for image captioning task. The first technique in the proposed model is where ResNet50 and MobileNet 
are used individually for feature extraction from images. They are then flattened and made to go through 
dense layers before being fused into one. This fusion gives a single feature vector that gives both the 
depth and efficiency of the two architectures. 
Keywords: Deep Learning, Image Captioning, ResNet50, MobileNet, Speech Synthesis, Flickr8k 
Dataset, Text-to-Speech (TTS), Multi-lingual Speech Output. 
