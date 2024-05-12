# Zero-Shot-Image-classification-with-CLIP
Using Gen AI CLIP model for zero shot image classification


CLIP, or Contrastive Language-Image Pretraining, is a neural network model developed by OpenAI that learns to understand and relate images and text in a unified manner. Unlike traditional computer vision models that are trained solely on images or natural language processing models trained only on text, CLIP is trained on a large dataset of images and associated text from the internet.

The key innovation of CLIP is its ability to learn visual concepts directly from natural language descriptions. By learning to associate images with the corresponding text descriptions, CLIP can understand the semantic relationship between images and text. This enables it to perform various tasks such as image classification, zero-shot image classification (where it can classify images into categories it hasn't been explicitly trained on), and image generation conditioned on text prompts.

Overall, CLIP represents a significant advancement in AI understanding of multimodal data, bridging the semantic gap between images and text and demonstrating impressive generalization capabilities across various tasks.

my task is to classify images that match one of three new characters Mario, Frieren and Lae'zel (examples in the notebook).

Along with the notebook, you'll find a dataset consisting of the following files:
- `images.tar`: a sample of images
- `embeddings.npy`: CLIP embeddings for the same images
- `test_set.csv`: a set of test labels for 100 images for three different characters

Code to load the images, embeddings and test set is included in the notebook.

## Deliverables

1. Implement a simple classifier for the three characters Mario, Frieren and Lae'zel based on the provided data.
2. Evaluate your classifier on the provided test set.
3. Comment on your approach and any considerations you made.


