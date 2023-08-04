# Frequently Asked Questions

## Where are the COVIDNet models?
Download the models from the links in the [pretrained models section](models.md).

## Where is the COVIDx dataset?
Due to limited cloud space, we cannot hold the entire dataset, so we provided [dataset generation scripts](COVIDx.md). To reproduce the results, we provided txt files, which contain the exact images we used for training and testing.

## How can I contribute?
Possible ways to contribute: provide more data, experiment with other model prototypes, validate model on external data, medical expertise.

## Why is test_COVIDxX.txt different than test set created?
To create a more balanced test set, since there are only 100 covid test samples, we randomly sampled 100 from normal and pneumonia.

## Can you provide the model/network architecture code?
Since this model is designed by GenSynth and have different microarchitecture designs in each module, we do not have the code available, but we provided the [training script](train_eval_inference.md) for retraining on the given pretrained models.


## Tried running the scripts but says that model doesn't exist. How to get them?
The models are not in the repo since they are large and over the Github file size limit of 100 MB. You have to download the models first and change the paths to point to where you put the models. Refer to steps in the [Training and Evaluation](train_eval_inference.md) section of the readme.
