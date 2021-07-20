# Big Sleep (Colabs)

User-friendly Colab notebooks for Big Sleep. Both notebooks are fully functional in Google Colab as of Jul 2021.

The notebooks produce very different results. VQGAN+CLIP notebook is able to produce larger images. BigGAN+CLIP is able to produce only 512x512 px images as per pretrained `biggan-deep-512` model. In addition to final image, both notebooks are able to save progression images (every nth iteration) as well as a progression video.

Big Sleep is originally a concept of turning text into imagery by using [CLIP](https://github.com/openai/CLIP) (OpenAI) to steer [BigGAN](https://arxiv.org/abs/1809.11096) (Andrew Brock et al.), as introduced by [Ryan Murdock](https://github.com/rynmurdock) in his [original notebook](https://colab.research.google.com/drive/1NCceX2mbiKOSlAd_o7IU7nA9UskKN5WR?usp=sharing).

---

**Colab for:** VQGAN+CLIP by [Katherine Crowson](https://github.com/crowsonkb)<br>
**Papers:** 1) [VQGAN by Patrick Esser et al](https://arxiv.org/abs/2012.09841), 2) [CLIP by OpenAI](https://arxiv.org/abs/2103.00020)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralImageGeneration/blob/main/BigSleep_crowsonkb.ipynb)

![image](https://user-images.githubusercontent.com/50331907/126226554-f53ae66d-21d9-428f-9c16-0a17bf8c0ef9.png)<br>
_Satanism in the 1900s_ at 400 iterations

---

**Colab for:** [Big Sleep (BigGAN+CLIP)](https://github.com/lucidrains/big-sleep) by [Phil Wang](https://github.com/lucidrains) (more precisely [this fork](https://github.com/olaviinha/big-sleep))<br>
**Papers:** 1) [BigGAN by Andrew Brock et al](https://arxiv.org/abs/1809.11096), 2) [CLIP by OpenAI](https://arxiv.org/abs/2103.00020)

This notebook is using the original Big Sleep technique.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralImageGeneration/blob/main/BigSleep_lucidrains.ipynb)

![image](https://user-images.githubusercontent.com/50331907/126226982-815e6fa6-6d5b-4d99-b1b1-902261a88212.png)<br>
_Satanism in the 1900s_ at 400 iterations
