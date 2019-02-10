
We used code from tensorflow tutorials https://www.tensorflow.org/hub/tutorials/image_retraining
So, we use pretrained model and change last fully connected layer
To train model and check accuracy - CUDA_VISIBLE_DEVICES=gpu_that_you_want_to_use python main.py --image_dir=data/.
But we achieved our best results with pytorch model (cause we don't like this fucking tensorflow) . To train model and check accuracy follow instructions in `train_classifier.ipynb`. Also we have additional augmentation in `augment_images.ipynb`

data: https://fex.net/946405155733

We got accuracy 98%

# WITH LOVE, pink_roses
