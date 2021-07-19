# Big Sleep (Colabs)

User-friendly Colab notebooks for Big Sleep. Both notebooks are fully functional in Google Colab as of Jul 2021.

The notebooks produce very different results. VQGAN+CLIP notebook is able to produce larger images. BigGAN+CLIP is able to produce only 512x512 px images as per pretrained `biggan-deep-512` model. In addition to final image, both notebooks are able to save progression images (every nth iteration) as well as a progression video.

Big Sleep is originally a concept of turning text into imagery by using [CLIP](https://github.com/openai/CLIP) by OpenAI to steer [BigGAN](https://arxiv.org/abs/1809.11096) by Andrew Brock et al., as introduced by [Ryan Murdock](https://github.com/rynmurdock) in his [original notebook](https://colab.research.google.com/drive/1NCceX2mbiKOSlAd_o7IU7nA9UskKN5WR?usp=sharing). 

Example images below were generated using the same string of text.

---

**Colab for:** VQGAN+CLIP by [Katherine Crowson](https://github.com/crowsonkb)<br>
**Papers:** [VQGAN by Patrick Esser et al](https://arxiv.org/abs/2012.09841), [CLIP by OpenAI](https://arxiv.org/abs/2103.00020)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralImageGeneration/blob/main/BigSleep_crowsonkb.ipynb)

---

**Colab for:** [Big Sleep (BigGAN+CLIP)](https://github.com/lucidrains/big-sleep) by [Phil Wang](https://github.com/lucidrains) (more precisely [this fork](https://github.com/olaviinha/big-sleep))<br>
**Papers:** [BigGAN by Andrew Brock et al](https://arxiv.org/abs/1809.11096) [CLIP by OpenAI](https://arxiv.org/abs/2103.00020)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralImageGeneration/blob/main/BigSleep_lucidrains.ipynb)
