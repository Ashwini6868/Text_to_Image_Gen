# Text_to_Image_Gen

## Install
!pip install torch torchvision transformers datasets accelerate diffusers huggingface_hub
!pip install datasets

## Collect Dataset from Huggingface
from datasets import load_dataset
dataset = load_dataset('poloclub/diffusiondb')

