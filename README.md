# StableDiffusion

This repository provides a Google Colab Notebook to run the text-to-image [Stable Diffusion](https://huggingface.co/CompVis/stable-diffusion-v1-4) model by CompVis.

It also provides a Google Colab Notebook to generate your own animated videos using text prompts.

## Usage
Run [`Stable_Diffusion.ipynb`](https://colab.research.google.com/github/daparasyte/StableDiffusion/blob/main/Stable_Diffusion.ipynb) to generate images using text.   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/daparasyte/StableDiffusion/blob/main/Stable_Diffusion.ipynb)

Run [`Stable_Diffusion_Animation.ipynb`](https://colab.research.google.com/github/daparasyte/StableDiffusion/blob/main/Stable_Diffusion_Animation.ipynb) to produce your own animated videos using text prompts.   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/daparasyte/StableDiffusion/blob/main/Stable_Diffusion_Animation.ipynb)




## Saftey Check
To remove the safety check, switch `remove_safety` to `True`:
```
remove_safety = True
```

## Schedulers
* PNDM, which is the default scheduler in HuggingFace's Diffusers for Stable Diffusion
* DDIM
* K-LMS, which is the scheduler suggested by [DreamStudio](https://stabilityai.us.auth0.com/u/login?state=hKFo2SA0Y1lYdlhsdXRJU2hKZWV6em5faDN2aEozSXdReUl0YaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHJCeDVKZWdRMHE2RkstWkpMVzYwWmVuamREeDJiZ2hLo2NpZNkgS3ZZWkpLU2htVW9PalhwY2xRbEtZVXh1Y0FWZXNsSE4)

## Resources
* [Paper: Understanding Diffusion Models: A Unified Perspective](https://arxiv.org/abs/2208.11970)
* [Awesome-diffusion-models](Awesome-diffusion-models)
* [CompVis - stable diffusion v1.4](https://huggingface.co/CompVis/stable-diffusion-v1-4)
