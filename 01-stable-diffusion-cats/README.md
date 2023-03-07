### Module 1: Stable Diffusion with Small Dataset of Cat Images
This repository showcases the Stable Diffusion technique, a powerful generative modeling technique that allows for the creation of high-quality images from small datasets. The repository consists of two Jupyter notebooks.

The first notebook, `01-txt2img-gen.ipynb`, demonstrates how to easily create a SageMaker endpoint for the pre-trained Stable Diffusion model and generate cat images based on user prompts. Users can input fun scenarios and prompts to generate various cat images.

<div>
    <img src="./../img/cat-3.png" alt="Image 3" width="400" style="display:inline-block">
    <img src="./../img/cat-4.png" alt="Image 4" width="400" style="display:inline-block">
</div>

The second notebook, `02-finetune.ipynb`, showcases the process of fine-tuning the Stable Diffusion model with a small set of images. This approach involves using images of cats from specific breeds or your own pet cats to teach the model how to recreate these images and incorporate them into various creative scenarios. This technique can be adapted to work with any set of images containing fewer than ten examples, such as images of pet dogs or other entities.

By following the steps outlined in the notebook, you can collect a few images of your chosen entity from Google Images and utilize the fine-tuning process to train the Stable Diffusion model to create new and unique compositions. This approach offers a broad range of creative possibilities, allowing you to experiment with various scenarios and unleash your imagination.

<div>
    <img src="./../img/cat-1.png" alt="Image 1" width="400" style="display:inline-block">
    <img src="./../img/cat-2.png" alt="Image 2" width="400" style="display:inline-block">
</div>

Overall, this repository provides users with a powerful tool for generating high-quality images, even with limited datasets. The Stable Diffusion technique offers a versatile and efficient way to create customized and imaginative images.