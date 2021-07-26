# Big Sleep colabs (neural text-to-image)

User-friendly Colab notebooks for Big Sleep and its offsprings. All notebooks are fully functional in Google Colab as of Jul 2021.

Big Sleep is originally a concept of turning text into imagery by using [CLIP](https://github.com/openai/CLIP) (OpenAI) to steer [BigGAN](https://arxiv.org/abs/1809.11096) (Andrew Brock et al.), as introduced by [Ryan Murdock](https://github.com/rynmurdock) in his [original notebook](https://colab.research.google.com/drive/1NCceX2mbiKOSlAd_o7IU7nA9UskKN5WR?usp=sharing). Technique has since kept developing.

The point of these notebooks has been a user-friendly and quick-to-run UI, but some basic features have also been added, such as saving selected progression images and progression video. All notebooks produce very different results. CLIP+VQGAN notebook (on top) is able to produce the largest images. 

---

**Colab for:** CLIP+VQGAN by [Katherine Crowson](https://github.com/crowsonkb)<br>
**Papers:** 1) [VQGAN by Patrick Esser et al](https://arxiv.org/abs/2012.09841), 2) [CLIP by OpenAI](https://arxiv.org/abs/2103.00020)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralImageGeneration/blob/main/CLIP%2BVQGAN_crowsonkb.ipynb)

![image](https://user-images.githubusercontent.com/50331907/126226554-f53ae66d-21d9-428f-9c16-0a17bf8c0ef9.png)<br>
400 iterations of _"Satanism in the 1900s"_.

---

**Colab for:** Latent Vision by [Ryan Murdock](https://github.com/rynmurdock)<br>
**Papers:** 1) [VQGAN by Patrick Esser et al](https://arxiv.org/abs/2012.09841), 2) [CLIP by OpenAI](https://arxiv.org/abs/2103.00020)

Results of this notebook is pretty much something between the original Big Sleep (below) and CLIP+VQGAN (above).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralImageGeneration/blob/main/LatentVision_rynmurdock.ipynb)

![image](https://user-images.githubusercontent.com/50331907/126967558-b68857b7-0792-4135-b535-687539a3d240.png)<br>
400 iterations of _"Satanism in the 1900s"_.

---

**Colab for:** [Big Sleep (CLIP+BigGAN)](https://github.com/lucidrains/big-sleep) by [Phil Wang](https://github.com/lucidrains) (more precisely [this fork](https://github.com/olaviinha/big-sleep))<br>
**Papers:** 1) [BigGAN by Andrew Brock et al](https://arxiv.org/abs/1809.11096), 2) [CLIP by OpenAI](https://arxiv.org/abs/2103.00020)

This notebook is follows the original Big Sleep technique.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralImageGeneration/blob/main/BigSleep_lucidrains.ipynb)

![image](https://user-images.githubusercontent.com/50331907/126226982-815e6fa6-6d5b-4d99-b1b1-902261a88212.png)<br>
400 iterations of _"Satanism in the 1900s"_.
