# StableDiffusion

This repository provides a Google Colab Notebook to run the text-to-image [Stable Diffusion](https://huggingface.co/CompVis/stable-diffusion-v1-4) model by CompVis.

## Saftey Check
To remove the safety check, switch `remove_safety` to `True`:
```
remove_safety = True
```

## Schedulers
* PNDM, which is the default scheduler in HuggingFace's Diffusers for Stable Diffusion
* DDIM
* K-LMS, which is the scheduler suggested by [DreamStudio](https://stabilityai.us.auth0.com/u/login?state=hKFo2SA0Y1lYdlhsdXRJU2hKZWV6em5faDN2aEozSXdReUl0YaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHJCeDVKZWdRMHE2RkstWkpMVzYwWmVuamREeDJiZ2hLo2NpZNkgS3ZZWkpLU2htVW9PalhwY2xRbEtZVXh1Y0FWZXNsSE4)

## Usage
Run [`Stable_Diffusion.ipynb`](https://colab.research.google.com/github/daparasyte/StableDiffusion/blob/main/Stable_Diffusion.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/daparasyte/StableDiffusion/blob/main/Stable_Diffusion.ipynb)
