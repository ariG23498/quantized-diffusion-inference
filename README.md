# Run diffusion models on a Free Colab Tier

A collection of scripts and notebooks that show how to **quantize** diffusion models and run them on a **free tier colab** notebook. We will be using the `diffusers` library to handle everything diffusion and `bitsandbytes` for everything quantization.

## How to navigate the repository?

You will find notebooks or script starting with `[Quant]` which signify that they will guide through the quantization model. The scripts with start with `[Inf]` signify inference only guides.

| Description | Colab Notebooks |
| :--: | :--: |
| Quantize Text to Video Generation model (CogVideoX) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ariG23498/quantized-diffusion-inference/blob/main/%5BQunat%5Dcog_video_x.ipynb) |
| Inference Text to Video Generation model (CogVideoX) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ariG23498/quantized-diffusion-inference/blob/main/%5BInf%5Dcog_video_x.ipynb) |
| Quantize Text to Image Generation model (Stable Diffusion 3) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ariG23498/quantized-diffusion-inference/blob/main/%5BQuant%5Dstable_diffusion_3.ipynb) |
| Inference Text to Image Generation model (Stable Diffusion 3) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ariG23498/quantized-diffusion-inference/blob/main/%5BInf%5Dstable_diffusion_3.ipynb) |