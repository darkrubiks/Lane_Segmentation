# Lane Segmentation for Autonomous Vehicle Navigation using Keras

![Image of Yaktocat](https://i.imgur.com/c4hkPJW.png)

## Contents

1. **data_preparation.ipynb**: Use this notebook for generating train, validation and test data ([Dataset TuSimple](https://github.com/TuSimple/tusimple-benchmark));
2. **train.ipynb**: Notebook with the training method, I used the following library [Segmentations Models](https://github.com/qubvel/segmentation_models);
3. **make_video.ipynb**: Notebook for making a video with all images on the test set.

#### Model: Resnet18 Backbone with Unet Architecture for Decoder Input: 512 width x 256 heigth x 3 channels
