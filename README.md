# Transfer Learning with YAMNet for Environmental Sound Classification

[YAMNet](https://tfhub.dev/google/yamnet/1) is a pre-trained deep neural network developed by Google that can classify audio events into [521 different classes](https://github.com/tensorflow/models/blob/master/research/audioset/yamnet/yamnet_class_map.csv), including everyday sounds such as laughter, barking, or a siren. Originally trained on a large corpus of diverse audio data from YouTube, YAMNet is capable of robustly recognizing a wide array of sound events.

In this tutorial, you will learn how to:

1. **Load and use the YAMNet model for inference:** You'll start by loading the pre-trained YAMNet model and using it to predict the classes of sounds in audio clips.

2. **Build a new model using YAMNet embeddings:** We'll use YAMNet as a feature extractor to create embeddings from your audio data. These embeddings will serve as the input for a new model that you will build and train to classify specific sounds such as cat and dog sounds.

3. **Evaluate and export your model:** After training, you'll evaluate the performance of your new model on a test dataset and learn how to save and export the model for later use.

This hands-on approach will provide you with practical experience and a solid foundation in applying deep learning techniques for environmental sound classification using transfer learning.
