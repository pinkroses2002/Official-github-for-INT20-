We use code from tensorflow tutorials https://www.tensorflow.org/hub/tutorials/image_retraining
So, we use pretrained model and change last fully connected layer
To train model and check accuracy - CUDA_VISIBLE_DEVICES=gpu_that_you_want_to_use python main.py --image_dir=data/

We got accuracy 