# GAN Image Generation with BigGAN

This project explores how Generative Adversarial Networks (GANs), using BigGAN, can generate realistic images from random noise using a pretrained model.

## Objective

- Understand how GANs work by interacting with pretrained models.
- Generate synthetic images from random noise vectors.
- Analyze and reflect on how changes to input vectors influence the image output.

## About GANs

Generative Adversarial Networks consist of two models:
- **Generator**: Produces fake images from noise.
- **Discriminator**: Tries to distinguish real from generated images.

The two models train adversarially, improving each other over time. In this project, I used a pretrained generator model to focus on inference and analysis.

## Tools & Libraries

- Python
- PyTorch
- Hugging Face Transformers
- Google Colab / Jupyter Notebook
- `torch`, `torchvision`, `transformers`, `matplotlib`, `PIL`

## How to Run

1. **Install required libraries**:
    ```bash
    pip install torch torchvision matplotlib transformers
    ```

2. **Run the notebook** (`gan_image_generation.ipynb`):
    - Open in Jupyter or Google Colab.
    - Generate images using random latent vectors.
    - Experiment using different seeds or truncation values.

3. **Customize**:
    - Adjust the latent vector.
    - Modify class vectors or truncation values.
    - Generate and save new images.

## Report
- Introduction to GANs
- Summary of the experiment
- Observations on image quality and variation
- Reflections on challenges, limitations, and learnings

## Deliverables

- Jupyter Notebook (`.ipynb`)
- Reflection Report