# News

See also the [Preview of Style2Paints V5](https://github.com/lllyasviel/style2paints/tree/master/V5_preview).
 
**Note that below are previous versions of style2paints. If you come from an introduction of V5 and are interested in V5, you do not need to download the V4 or V4.5. Note that V5 is still in preview and we have not released it yet.**
 
# Download Style2Paints V4.5

You can directly download the software (windows x64) at:

**Again, this is style2paints V4.5, NOT style2paints V5!**

Google Drive:

    https://drive.google.com/open?id=1gmg2wwNIp4qMzxqP12SbcmVAHsLt1iRE

Baidu Drive (百度网盘):

    https://pan.baidu.com/s/15xCm1jRVeHipHkiB3n1vzA
    
Online version of style2paints V4.5 https://highcwu-style2paints-4-5-gradio.hf.space/file/ui/web-mobile/index.html

Online version of style2paints V4 https://highcwu-style2paints-4-gradio.hf.space/file/ui/web-mobile/index.html

You do **NOT** need to install any complex things like CUDA and python. You can directly download it and then double click it, as if you were playing a normal video game.

Never hesitate to let me know if you have any suggestions or ideas. You may directly send emails to my private address [lvminzhang@acm.org] or [lvminzhang@siggraph.org].

# Welcome to style2paints V4!

![logo](https://github.com/lllyasviel/style2paints/raw/master/imgs/pages/logo.jpg)

Style2paints V4 is an AI driven lineart colorization tool.

[![](https://img.shields.io/github/repo-size/lllyasviel/style2paints.svg)](https://github.com/lllyasviel/style2paints)
[![](https://img.shields.io/github/license/lllyasviel/style2paints.svg)](https://github.com/lllyasviel/style2paints)
[![](https://img.shields.io/github/issues/lllyasviel/style2paints.svg)](https://github.com/lllyasviel/style2paints/issues)
[![](https://img.shields.io/github/stars/lllyasviel/style2paints.svg?label=Stars&style=social)](https://github.com/lllyasviel/style2paints/stargazers)
[![](https://img.shields.io/twitter/follow/lvminzhang.svg?label=Follow&style=social)](https://twitter.com/lvminzhang)


Different from previous end-to-end image-to-image translation methods, style2paints V4 is the **first** system to colorize a lineart **in real-life human workflow**, and the outputs are **layered**.

Inputs:

    ● Linearts
    ● (with or without) Human hints
    ● (with or without) Color style reference images
    ● (with or without) Light location and color

Outputs:

    ● Automatic color flattening without lines (solid/flat/inherent/固有色/底色 color layer)
    ● Automatic color flattening with black lines
    ● Automatic colorization without lines
    ● Automatic colorization with black lines
    ● Automatic colorization with colored lines
    ● Automatic rendering (separated layer)
    ● Automatic rendered colorization

Style2paints V4 gives you results of the current highest quality. You are able to get separated layers from our system. These layers can be directly used in your painting workflow. Different from all previous AI driven colorization tools, our results are not single 'JPG/PNG' images, and in fact, our results are 'PSD' layers.

User Instruction: [https://style2paints.github.io/](https://style2paints.github.io/)

And we also have an official [Twitter](https://twitter.com/lvminzhang) account.

# Help human in their standard coloring workflow!

Most human artists are familiar with this workflow:

    sketching -> color filling/flattening -> gradients/details adding -> shading

And the corresponding layers are:

    lineart layers + flat color layers + gradient layers + shading layers

Style2paints V4 is designed for this standard coloring workflow! In style2paints V4, you can automatically get separated results from each step!

# Examples

![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/pip.jpg)

Here we present some results in this ABCD format. Users only need to upload their sketch, select a style, and put a light source. 

When the result is achieved immediately without any human color correction, we regard this result as **fully automatic result**. When the result needs some color correction, human can easily put some color hints on the canvas to guide the AI coloring process. In this case, we regard these results as **semi-automatic results**. If a result is semi-automatic, but the quantity of human color hint points is smaller than 10, we regard these results as **almost automatic result**. In this section, about half of the presented results are **fully automatic result**, and the others are all **almost automatic result**. Do notice that all the below results can be achieved with less than 15 clicks!

![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/5.jpg)

![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/1.jpg)

# Real-life results

![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/a.png)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/b.png)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/1.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/2.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/3.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/4.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/5.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/6.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/7.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/8.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/9.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/10.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/11.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/12.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/13.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/14.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/15.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/16.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/17.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/18.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/19.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/20.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/21.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/22.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/23.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/24.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/25.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/26.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/27.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/28.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/29.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/30.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/31.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/32.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/33.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/34.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/35.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/36.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/37.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/38.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/39.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/40.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/41.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/42.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/43.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/44.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/45.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/46.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/47.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/48.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/49.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/50.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/51.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/52.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/53.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/54.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/55.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/56.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/57.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/58.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/59.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/60.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/61.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/62.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/63.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/64.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/65.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/66.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/67.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/68.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/69.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/70.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/71.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/72.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/73.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/74.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/75.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/76.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/77.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/78.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/79.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/80.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/81.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/82.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/83.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/84.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/85.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/86.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/87.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/88.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/89.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/90.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/91.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/92.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/93.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/94.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/95.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/96.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/97.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/98.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/99.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/100.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/101.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/102.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/103.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/104.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/105.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/106.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/107.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/108.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/109.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/110.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/111.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/112.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/113.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/114.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/115.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/116.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/117.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/118.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/119.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/120.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/121.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/122.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/123.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/124.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/125.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/126.jpg)
![logo](https://github.com/lllyasviel/style2paints/raw/master/temps/show/t/127.jpg)

# Know more about us!

User Instruction: [https://style2paints.github.io/](https://style2paints.github.io/)

And we also have an official [Twitter](https://twitter.com/IlIIlIIIllIllII) account.

# Acknowledgement

Thanks a lot to TaiZan. This project could not be achieved without his great help.

# Lisence

All codes are released in Apache-2.0 License.

We preserve all rights on all pretrained deep learning models and binary releases.

Your colorized images are yours, and we do not add any extra lisences to colorized results. Use your colorized images in any commercial or non-commercial cases.

# 中文社区

我们有一个除了技术什么东西都聊的以技术交流为主的群。如果你一次加群失败，可以多次尝试: 816096787。

# Previous Publications

## Style2paints V1:

ACPR 2017:

    @Article{ACPR2017ZLM,
      author  = {LvMin Zhang, Yi Ji and ChunPing Liu},
      title   = {Style Transfer for Anime Sketches with Enhanced Residual U-net and Auxiliary Classifier GAN},
      conference = {Asian Conference on Pattern Recognition (ACPR)},
      year    = {2017},
    }

[paper](https://arxiv.org/abs/1706.03319)

## Style2paints V2:

No Publications.

## Style2paints V3:

TOG 2018:

    @Article{ACMTOGTSC2018,
      author  = {LvMin Zhang, Chengze Li, Tien-Tsin Wong, Yi Ji and ChunPing Liu},
      title   = {Two-stage Sketch Colorization},
      journal = {ACM Transactions on Graphics},
      year    = {2018},
      volume  = {37},
      number  = {6},
      month   = nov,
      doi     = {https://doi.org/10.1145/3272127.3275090},
    }

[paper](https://github.com/lllyasviel/style2paints/blob/master/papers/sa.pdf)

## Style2paints V4:

No Publications.

## Style2paints V5 (Project SEPA, not released yet):

CVPR2021

    @InProceedings{Filling2021zhang,
      author={Lvmin Zhang and Chengze Li and Edgar Simo-Serra and Yi Ji and Tien-Tsin Wong and Chunping Liu}, 
      booktitle={IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
      title={User-Guided Line Art Flat Filling with Split Filling Mechanism}, 
      year={2021}, 
    }







