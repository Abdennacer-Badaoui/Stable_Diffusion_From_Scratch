# 🖼️ Stable Diffusion from Scratch

Welcome to the **Stable Diffusion from Scratch** project! This repository contains the implementation of the Stable Diffusion model 1.5, built entirely from the ground up.

## What Is It?

Stable Diffusion is a state-of-the-art model for generating high-quality images from text prompts. It works by gradually transforming random noise into a detailed image, guided by the input text.

## Why Did I Build This?

I built this project to deeply understand the inner workings of diffusion models and to challenge myself to recreate a complex machine learning model from scratch. This implementation breaks down the process into manageable components, providing a clear view of how each part contributes to the final result.

## 🚀 Quick Start

Clone the repo, install dependencies, and start exploring:

```bash
git clone https://github.com/Newbyl/SD_From_Scratch.git
cd stable-diffusion-from-scratch
pip install -r requirements.txt
```

Download the pretrained weights named `v1-5-pruned-emaonly.ckpt` [here](https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main) and also the `vocab.json` and `merge.txt` from here [there](https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main/tokenizer) and put them in the `data` folder.

You will find in the `demo.ipynb` notebook some code to generate images.
