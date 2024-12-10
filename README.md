# Text_to_Image_Gen

## Install
To set up the environment, use the following commands:

```bash
pip install torch torchvision transformers datasets accelerate diffusers huggingface_hub
pip install datasets


## Collect Dataset from Huggingface

from datasets import load_dataset
dataset = load_dataset('poloclub/diffusiondb')

##Results

**Note:**
- Replace `path/to/your/image.jpg` with the actual path or URL to the image you want to display. If the image is stored in your repository, you can use relative paths like `./images/my_image.jpg` or host it elsewhere and use the URL.




