# Neural text-to-image (Big Sleep etc.)

User-friendly Colab notebooks for Big Sleep, its siblings and offsprings.

Big Sleep is originally a concept of turning text into imagery by using [CLIP](https://github.com/openai/CLIP) (OpenAI) to steer [BigGAN](https://arxiv.org/abs/1809.11096) (Andrew Brock et al.), as introduced by [Ryan Murdock](https://github.com/rynmurdock) in his [original notebook](https://colab.research.google.com/drive/1NCceX2mbiKOSlAd_o7IU7nA9UskKN5WR?usp=sharing). The technique has since branched and evolved.

There are countless versions of these notebooks out there. The point of these notebooks is a user-friendly and quick-to-run UI. Some additional basic features have also been added to some notebooks, such as saving all/selected progression images and progression video, batch processing, etc. All notebooks produce very different results.

I do not use all of these notebooks on a regular basis, so please do raise an issue should any problems occur.

---

**Colab for:** ruDALLE by [Sberbank-AI](https://github.com/sberbank-ai)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToImage/blob/main/ruDalle.ipynb)

![image](https://user-images.githubusercontent.com/50331907/159492943-572f7a52-83a9-4310-befb-ceb8473af77d.png)
<br>
_"Satanism in the 1900s"_

---

**Colab for:** JAX CLIP Guided Diffusion by [nshepperd](https://github.com/nshepperd)<br>
Method originally by [Katherine Crowson](https://github.com/crowsonkb)<br>

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToImage/blob/main/JAX_CLIP_Guided_diffusion_nshepperd.ipynb)

![image](https://user-images.githubusercontent.com/50331907/144711796-3933dbb1-d8a0-4656-812f-050ccb444118.png)
<br>
300 iterations of _"Satanism in the 1900s"_.

---

**Colab for:** CLIP+VQGAN by [Katherine Crowson](https://github.com/crowsonkb)<br>
**Papers:** 1) [VQGAN by Patrick Esser et al](https://arxiv.org/abs/2012.09841), 2) [CLIP by OpenAI](https://arxiv.org/abs/2103.00020)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToImage/blob/main/CLIP%2BVQGAN_crowsonkb.ipynb)

![image](https://user-images.githubusercontent.com/50331907/126226554-f53ae66d-21d9-428f-9c16-0a17bf8c0ef9.png)<br>
400 iterations of _"Satanism in the 1900s"_.

---

**Colab for:** Latent Vision by [Ryan Murdock](https://github.com/rynmurdock)<br>
**Papers:** 1) [VQGAN by Patrick Esser et al](https://arxiv.org/abs/2012.09841), 2) [CLIP by OpenAI](https://arxiv.org/abs/2103.00020)

Results of this notebook are pretty much something between the original Big Sleep (below) and CLIP+VQGAN (above).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToImage/blob/main/LatentVision_rynmurdock.ipynb)

![image](https://user-images.githubusercontent.com/50331907/126967558-b68857b7-0792-4135-b535-687539a3d240.png)<br>
400 iterations of _"Satanism in the 1900s"_.

---

**Colab for:** [Big Sleep (CLIP+BigGAN)](https://github.com/lucidrains/big-sleep) by [Phil Wang](https://github.com/lucidrains) (more precisely [this fork](https://github.com/olaviinha/big-sleep))<br>
**Papers:** 1) [BigGAN by Andrew Brock et al](https://arxiv.org/abs/1809.11096), 2) [CLIP by OpenAI](https://arxiv.org/abs/2103.00020)

This notebook follows the original Big Sleep technique.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToImage/blob/main/BigSleep_lucidrains.ipynb)

![image](https://user-images.githubusercontent.com/50331907/126226982-815e6fa6-6d5b-4d99-b1b1-902261a88212.png)<br>
400 iterations of _"Satanism in the 1900s"_.
