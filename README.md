# Oracle-Image-Restoration
Oracle Bone Inscription Image Restoration via Glyph Extraction

All codes can be found in the GlyphUnet folder.

### Files:
1. datasets.py: loading images from target path
2. train.py: Model training pipeline


### Folders:
1. data: datasets for training and testing
2. models: different NN models
3. util: Tools for utilizing the model training, or additional processing like visualization.
4. wandb: wandb recoder for result/parameter visualization (optional)


### Requirements:
+ CUDA==10.2
+ cudnn==8.0
+ python==3.6
+ torch==1.8.0
+ torchvision==0.9.0
+ DNN-printer==0.0.2
+ numpy
+ tqdm
+ wandb (optional)
+ argparse
+ wmi (optional)
