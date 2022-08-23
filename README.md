# Neural text-to-image Colab notebooks

User-friendly Colab notebooks for various text-to-image methods.

**Available notebooks:**

- [Stable Diffusion](#stable-diffusion-by-compvis-stability-ai-and-laion)
- [DALL·E Mini (craiyon.ai)](#dalle-mini-craiyonai-by-boris-dayma)
- [Latent Diffusion LAION 400M](#latent-diffusion-laion-400m-by-compvis)
- [ruDALLE Malevich](#rudalle-malevich-by-sberbank-ai)
- [JAX CLIP Guided Diffusion](#jax-clip-guided-diffusion-by-nshepperd)
- [CLIP+VQGAN](#clipvqgan-by-katherine-crowson)
- [Latent Vision](#latent-vision-by-ryan-murdock)
- [Big Sleep](#big-sleep-by-phil-wang-more-precisely-this-fork)

---

These techniques are all more or less descendants of Big Sleep, the original concept of turning text into imagery by using [CLIP](https://github.com/openai/CLIP) (OpenAI) to steer [BigGAN](https://arxiv.org/abs/1809.11096) (Andrew Brock et al.), as introduced by [Ryan Murdock](https://github.com/rynmurdock) in his [original notebook](https://colab.research.google.com/drive/1NCceX2mbiKOSlAd_o7IU7nA9UskKN5WR?usp=sharing). The technique has since branched and evolved.

There are countless versions of these notebooks out there. The point of this set of notebooks is a user-friendly and quick-to-run UI. Some additional basic features have also been added to some of the notebooks, such as saving all/selected progression images, saving progression video, batch processing, etc. 

I do not use these notebooks on a regular basis, and hence I'm mostly unaware when some library gets updated and a notebook may no longer function; Please do raise an issue should any problems occur.

---

## Stable Diffusion by [CompVis](https://github.com/CompVis), [Stability AI](https://stability.ai) and [LAION](https://laion.ai)

This colab requires registering with [Hugging Face](https://huggingface.co) for login token and [accepting model card terms](https://huggingface.co/CompVis/stable-diffusion-v1-4) to download required models.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToImage/blob/main/Stable_Diffusion.ipynb)

---

## DALL·E Mini (craiyon.ai) by [Boris Dayma](https://github.com/borisdayma)

This colab requires registering with [wandb](https://wandb.ai/) for an authentication key to download required models.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToImage/blob/main/dalle_mini.ipynb)

![image](https://user-images.githubusercontent.com/50331907/179073528-935fe0d2-363e-438b-9706-3e4548dd7569.png)

_"Satanism in the 1900s"_

---

## Latent Diffusion LAION 400M by [CompVis](https://github.com/CompVis)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToImage/blob/main/LAION_400M.ipynb)

![image](https://user-images.githubusercontent.com/50331907/163890889-a31370e6-e08d-4389-86af-947fe70a7140.png)

_"Satanism in the 1900s"_ (upscaled)

---

## ruDALLE Malevich by [Sberbank-AI](https://github.com/sberbank-ai)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToImage/blob/main/ruDalle.ipynb)

![image](https://user-images.githubusercontent.com/50331907/159492943-572f7a52-83a9-4310-befb-ceb8473af77d.png)
<br>
_"Satanism in the 1900s"_

---

## JAX CLIP Guided Diffusion by [nshepperd](https://github.com/nshepperd)<br>
Method originally by [Katherine Crowson](https://github.com/crowsonkb)<br>

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToImage/blob/main/JAX_CLIP_Guided_diffusion_nshepperd.ipynb)

![image](https://user-images.githubusercontent.com/50331907/144711796-3933dbb1-d8a0-4656-812f-050ccb444118.png)
<br>
300 iterations of _"Satanism in the 1900s"_.

---

## CLIP+VQGAN by [Katherine Crowson](https://github.com/crowsonkb)<br>
**Papers:** 1) [VQGAN by Patrick Esser et al](https://arxiv.org/abs/2012.09841), 2) [CLIP by OpenAI](https://arxiv.org/abs/2103.00020)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToImage/blob/main/CLIP%2BVQGAN_crowsonkb.ipynb)

![image](https://user-images.githubusercontent.com/50331907/126226554-f53ae66d-21d9-428f-9c16-0a17bf8c0ef9.png)<br>
400 iterations of _"Satanism in the 1900s"_.

---

## Latent Vision by [Ryan Murdock](https://github.com/rynmurdock)<br>
**Papers:** 1) [VQGAN by Patrick Esser et al](https://arxiv.org/abs/2012.09841), 2) [CLIP by OpenAI](https://arxiv.org/abs/2103.00020)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToImage/blob/main/LatentVision_rynmurdock.ipynb)

![image](https://user-images.githubusercontent.com/50331907/126967558-b68857b7-0792-4135-b535-687539a3d240.png)<br>
400 iterations of _"Satanism in the 1900s"_.

---

## Big Sleep by [Phil Wang](https://github.com/lucidrains) (more precisely [this fork](https://github.com/olaviinha/big-sleep))<br>
**Papers:** 1) [BigGAN by Andrew Brock et al](https://arxiv.org/abs/1809.11096), 2) [CLIP by OpenAI](https://arxiv.org/abs/2103.00020)

Original Big Sleep method.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToImage/blob/main/BigSleep_lucidrains.ipynb)

![image](https://user-images.githubusercontent.com/50331907/126226982-815e6fa6-6d5b-4d99-b1b1-902261a88212.png)<br>
400 iterations of _"Satanism in the 1900s"_.
