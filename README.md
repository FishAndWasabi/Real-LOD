<p align="center">
  <a href="">
    <img src='assets/logo.svg' alt='ICLR2025_REALLOD_LOGO' width="250px"/><br/>
  </a>
</p>

<h2> <p align=center> [ICLR2025] Re-Aligning Language to Visual Objects with an Agentic Workflow </p> </h2>

<div align="center">

📄 [**Table of Contents**](#-table-of-contents) | 🛠️ [**Install**](#️-dependencies-and-installation-) | 📖 [**Citation**](#-citation-) | 📜 [**License**](#-license-) | ❓ [**FAQ**]()

</div>

<span style="font-size: 18px;"><b>Note:</b> This repository is also a <span style="color: orange;"><a href="https://github.com/open-mmlab/mmdetection">MMDetection</a> style</span> codebase for Languaged-based Object Detection! Please feel free to use it for your own projects! If this repo helps you, please consider giving us a :star2:! </span>

<b>TL; DR:</b>  An agentic workflow including planning, tool use, and reflection steps to improve the alignment quality of language expressions and visual objects for LOD model.

This repository contains the official implementation of the following paper:

> **Re-Aligning Language to Visual Objects with an Agentic Workflow** </br>
> [Yuming Chen](http://www.fishworld.site/), [Jiangyan Feng](https://github.com/jyFengGoGo)<sup>\*</sup>, [Haodong Zhang](https://openreview.net/profile?id=~Haodong_Zhang2)<sup>\*</sup>, [Lijun Gong](https://scholar.google.com.hk/citations?user=CvmpmS0AAAAJ&hl=en), [Feng Zhu](https://zhufengx.github.io/), [Rui Zhao](https://zhaorui.xyz/), [Qibin Hou](https://houqb.github.io/)<sup>\#</sup>, [Ming-Ming Cheng](https://mmcheng.net), [Yibing Song](https://ybsong00.github.io/)<sup>\#</sup> </br>
> (\* denotes equal contribution. \# denotes the corresponding author.) </br>
> ICLR 2025 Conference </br>


## 📄 Table of Contents

- [📄 Table of Contents](#-table-of-contents)
- [✨ News 🔝](#-news-)
- [🛠️ Dependencies and Installation 🔝](#️-dependencies-and-installation-)
- [🤖 Real-Agent 🔝](#-real-agent-)
- [🏡 Real-Data 🔝](#-real-data-)
- [🏗️ Real-Model 🔝](#️-real-model-)
- [📖 Citation 🔝](#-citation-)
- [📜 License 🔝](#-license-)
- [📮 Contact 🔝](#-contact-)
- [🤝 Acknowledgement 🔝](#-acknowledgement-)


## ✨ News [🔝](#-table-of-contents)

- **Apr, 2025**: Our code is publicly available!
- **Jan, 2025**: 🔥 Our paper is accepted by ICLR 2025!

## 🛠️ Dependencies and Installation [🔝](#-table-of-contents)

> We provide a simple scrpit `install.sh` for installation, or refer to [install.md](docs/install.md) for more details.

1. Clone and enter the repo.

   ```shell
   git@github.com:FishAndWasabi/Real-LOD.git
   cd Real-LOD
   ```

2. Run `install.sh`.

   ```shell
   bash install.sh
   ```

3. Activate your environment!

   ```shell
   conda activate Real-LOD
   ```


## 🤖 Real-Agent [🔝](#-table-of-contents)

### Finetuning

### Workflow

### Examples

<p align="center">
  <a href="">
    <img src='assets/real-lod_examples.png' alt='ICLR2025_REALMODEL_EXAMPLES'/><br/>
  </a>
</p>

## 🏡 Real-Data [🔝](#-table-of-contents)

The annotations of our InDET dataset are in refcoco format and you can download from Google Drive or Baidu Pan. The images in our InDET dataset contains images from RefCOCO/g/+ (RefCOCO/g/+ images come from MSCOCO), Flicker30K entities, and Objects365 v2 (we sample 6000 images). Please follow their instructions to download the images and put them under a base data directory in the following structure.

```bash
├── refcoco
│   ├── refcoco+
│   │   ├── train2014
```


## 👼 Real-Model [🔝](#-table-of-contents)

### Train

### Evaluation

### Inference

### Examples

<p align="center">
  <a href="">
    <img src='assets/real-model_examples.png' alt='ICLR2025_REALMODEL_EXAMPLES'/><br/>
  </a>
</p>

## 📖 Citation [🔝](#-table-of-contents)

If you find our repo useful for your research, please cite us:

```
@inproceedings{chen2025realigning,
  title={Re-Aligning Language to Visual Objects with an Agentic Workflow},
  author={Yuming Chen and Jiangyan Feng and Haodong Zhang and Lijun GONG and Feng Zhu and Rui Zhao and Qibin Hou and Ming-Ming Cheng and Yibing Song},
  booktitle={The Thirteenth International Conference on Learning Representations},
  year={2025},
  url={https://openreview.net/forum?id=MPJ4SMnScw}
}
```

There are also relvant citations for other outstanding works in this repo:

```
@inproceedings{dang2024instructdet,
  title={Instruct{DET}: Diversifying Referring Object Detection with Generalized Instructions},
  author={Ronghao Dang and Jiangyan Feng and Haodong Zhang and Chongjian GE and Lin Song and Lijun GONG and Chengju Liu and Qijun Chen and Feng Zhu and Rui Zhao and Yibing Song},
  booktitle={The Twelfth International Conference on Learning Representations},
  year={2024},
  url={https://openreview.net/forum?id=hss35aoQ1Y}
}

@article{mmdetection,
  title   = {{MMDetection}: Open MMLab Detection Toolbox and Benchmark},
  author  = {Chen, Kai and Wang, Jiaqi and Pang, Jiangmiao and Cao, Yuhang and
             Xiong, Yu and Li, Xiaoxiao and Sun, Shuyang and Feng, Wansen and
             Liu, Ziwei and Xu, Jiarui and Zhang, Zheng and Cheng, Dazhi and
             Zhu, Chenchen and Cheng, Tianheng and Zhao, Qijie and Li, Buyu and
             Lu, Xin and Zhu, Rui and Wu, Yue and Dai, Jifeng and Wang, Jingdong
             and Shi, Jianping and Ouyang, Wanli and Loy, Chen Change and Lin, Dahua},
  journal= {arXiv preprint arXiv:1906.07155},
  year={2019}
}
```

## 📜 License [🔝](#-table-of-contents)

This code is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/) for non-commercial use only.
Please note that any commercial use of this code requires formal permission prior to use.

## 📮 Contact [🔝](#-table-of-contents)

For technical questions, please contact `chenyuming[AT]mail.nankai.edu.cn`.

For commercial licensing, please contact `cmm[AT]nankai.edu.cn`.

## 🤝 Acknowledgement [🔝](#-table-of-contents)

This repository borrows heavily from [mmdetection](https://github.com/open-mmlab/mmdetection), [grounding-dino](https://github.com/IDEA-Research/GroundingDINO), [peft](https://github.com/huggingface/peft), [transformers](https://github.com/huggingface/transformers),and [chatglm](https://github.com/THUDM/ChatGLM-6B).

For images from COCO, Objects365 and OpenImage, please see and follow their terms of use: [MSCOCO](https://cocodataset.org/#download)), [Objects365 v2](https://www.objects365.org/overview.html), and [OpenImage](https://storage.googleapis.com/openimages/web/index.html).

The README file is referred to [LED](https://github.com/Srameo/LED) and [LE3D](https://github.com/Srameo/LE3D/blob/main/README.md?plain=1).

We also thank all of our contributors.

<a href="https://github.com/FishAndWasabi/RealLOD/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=FishAndWasabi/RealLOD" />
</a>
