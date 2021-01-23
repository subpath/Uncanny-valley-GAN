# Uncanny-valley-GAN
BigGan that can generate only  creepy uncanny valley looking pictures

## Inspired by:
1. BigGAN* - <a target="_blank" href="https://colab.research.google.com/github/tensorflow/hub/blob/master/examples/colab/biggan_generation_with_tf_hub.ipynb"><img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Google Colab</a>
2. [Deep Dream](https://en.wikipedia.org/wiki/DeepDream)

<sub>* it's actually exactly the BigGan</sup>

## What it's about?

The idea is to ask BigGan to interpolate between two pictures from different categories and take this middle picture

Example 1 | Example 2 | Example 3
--- | --- | --- |
![](pics/pic1.png) | ![](pics/pic2.png) | ![](pics/pic3.png)

Example 4 | Example 5 | Example 6
--- | --- | --- |
![](pics/pic4.png) | ![](pics/pic5.png) | ![](pics/pic6.png)

## Try it out in the Google Colab:
https://colab.research.google.com/drive/1cfLXs8B9H4_cC-gpPF3BrHISulFw-DNK?usp=sharing