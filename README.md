# Curated Fashion AI

![cover](./outline.svg)

Fashion study is an interesting interdisciplinary subject between computer vision, natural language processing, recommendation system and fashion design etc. The research about fashion and artificial intelligence (AI) is rapidly evolved in this decade. This repository curates recent researches and resources about fashion and AI, hopes to help researchers who are interested in this field.

The following content is divided according to different subjects:

<details><summary>Table of Contents</summary><p>

* [Papers](#1-papers)
* [Workshops](#2-workshops)
* [Datasets](#3-datasets)
* [Companies](#4-companies)
</p></details><p></p>

## 1. Papers

### 1.1 Fashion recognition

* [DeepFashion: Powering Robust Clothes Recognition and Retrieval with Rich Annotations](https://liuziwei7.github.io/projects/DeepFashion.html)
* [Learning the Latent "Look"](http://vision.cs.utexas.edu/projects/StyleEmbedding/)

### 1.2 Fashion Detection

* [Layout-Graph Reasoning for Fashion Landmark Detection](http://openaccess.thecvf.com/content_CVPR_2019/papers/Yu_Layout-Graph_Reasoning_for_Fashion_Landmark_Detection_CVPR_2019_paper.pdf)
* [DeepMark: One-Shot Clothing Detection](http://openaccess.thecvf.com/content_ICCVW_2019/papers/CVFAD/Sidnev_DeepMark_One-Shot_Clothing_Detection_ICCVW_2019_paper.pdf)

### 1.3 Fashion Recommendation

#### 1.3.1 Pairwise Recommendation

* [Context-Aware Visual Compatibility Prediction](http://openaccess.thecvf.com/content_CVPR_2019/papers/Cucurull_Context-Aware_Visual_Compatibility_Prediction_CVPR_2019_paper.pdf)
* [Tiered Deep Similarity Search for Fashion](https://rose.ntu.edu.sg/Publications/Documents/Fashion%20Analytics/Tiered%20Similarity%20Search%20for%20Fashion.pdf)
* [TransNFCM: Translation-Based Neural Fashion Compatibility Modeling](https://arxiv.org/abs/1812.10021)

#### 1.3.2 Outfit Compatibility

* [POG: Personalized Outfit Generation for Fashion Recommendation at Alibaba iFashion](https://arxiv.org/pdf/1905.01866.pdf)

#### 1.3.3 Compatibility Interpretation

* [Outfit Compatibility Prediction and Diagnosis with Multi-Layered Comparison Network](https://arxiv.org/abs/1907.11496)
* [Interpretable Fashion Matching with Rich Attributes](http://staff.ustc.edu.cn/~hexn/papers/sigir19-fashion.pdf)
* [Personalized Fashion Recommendation with Visual Explanations based on Multimodal Attention Network](http://www.yongfeng.me/attach/chen-sigir2019.pdf)
* [Explainable Fashion Recommendation: A Semantic Attribute Region Guided Approach](https://arxiv.org/pdf/1905.12862v1.pdf)

#### 1.3.4 Wardrobe Creation

* [Creating Capsule Wardrobes from Fashion Images](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hsiao_Creating_Capsule_Wardrobes_CVPR_2018_paper.pdf)
* [Personalized Capsule Wardrobe Creation with Garment and User Modeling](https://liqiangnie.github.io/paper/PersonalizedCapsuleWardrobeCreationwithGarmentandUserModeling.pdf)

### 1.4 Image-based Virtual Try-on

* [VITON: An Image-based Virtual Try-on Network](http://openaccess.thecvf.com/content_cvpr_2018/papers/Han_VITON_An_Image-Based_CVPR_2018_paper.pdf)
* [Virtually Trying on New Clothing with Arbitrary Poses](https://xuemengsong.github.io/fp452-zhengA.pdf)

### 1.5 Fashion Editing

* [Fashion++: Minimal Edits for Outfit Improvement](https://arxiv.org/abs/1904.09261)
* [Fashion Editing with Multi-scale Attention Normalization](https://arxiv.org/abs/1906.00884)
* [Fashion-AttGAN: Attribute-Aware Fashion Editing with Multi-Objective GAN](https://arxiv.org/abs/1904.07460)
* [Compatible and Diverse Fashion Image Inpainting](https://arxiv.org/abs/1902.01096)

### 1.6 3D Garment

* [Deep Fashion3D: A Dataset and Benchmark for 3D Garment Reconstruction from Single Images](https://arxiv.org/pdf/2003.12753v1.pdf)

### 1.7 Fit and Size Recommendation

* [Decomposing Fit Semantics for Product Size Recommendation in Metric Spaces](http://cseweb.ucsd.edu/~jmcauley/pdfs/recsys18e.pdf)

## 2. Workshops

* [ICCV 2019 Second Workshop on Computer Vision for Fashion, Art and Design](https://sites.google.com/view/cvcreative/home?authuser=0)

## 3. Datasets

|                         | Image              | Text               | Category           | Attribute          | Landmark | Box | Mask               | Relation      | Other     |
|-------------------------|--------------------|--------------------|--------------------|--------------------|----------|-----|--------------------|---------------|-----------|
| [ACWS][1]               | :white_check_mark: |                    | :white_check_mark: |                    |          |     |                    |               |           |
| [Hipster Wars][11]      | :white_check_mark: |                    | :white_check_mark: |                    |          |     |                    |               |           |
| [Clothing1M][2]         | :white_check_mark: |                    |                    | :white_check_mark: |          |     |                    |               |           |
| [DCSA][3]               | :white_check_mark: |                    |                    | :white_check_mark: |          |     |                    |               |           |
| [Paperdoll][13]         | :white_check_mark: |                    |                    |                    |          |     | :white_check_mark: |               |           |
| [co-parsing][14]        | :white_check_mark: |                    |                    |                    |          |     | :white_check_mark: |               |           |
| [DeepFashion][4]        | :white_check_mark: |                    | :white_check_mark: | :white_check_mark: |          |     |                    | street2shop   |           |
| [DeepFashion2][5]       | :white_check_mark: |                    | :white_check_mark: | :white_check_mark: |          |     | :white_check_mark: | street2shop   |           |
| [imaterialist-2018][6]  | :white_check_mark: |                    | :white_check_mark: | :white_check_mark: |          |     |                    |               |           |
| [imaterialist-2019][7]  | :white_check_mark: |                    | :white_check_mark: | :white_check_mark: |          |     | :white_check_mark: |               |           |
| [WTBI][8]               | :white_check_mark: |                    |                    |                    |          |     |                    | street2shop   |           |
| [StreetStyle][9]        | :white_check_mark: |                    |                    | :white_check_mark: |          |     |                    |               | TimeStamp |
| [FashionVC][10]         | :white_check_mark: | :white_check_mark: |                    |                    |          |     |                    | Compatiblity  |           |
| [Polyvore-Maryland][15] | :white_check_mark: | :white_check_mark: | :white_check_mark: |                    |          |     |                    | Compatibility |           |
| [MVC][12]               | :white_check_mark: |                    |                    |                    |          |     |                    |               | MultiView |
| [ModaNet][16]               | :white_check_mark: |                    |                    |                    |          |     |  :white_check_mark: |               |       |

[1]: https://data.vision.ee.ethz.ch/cvl/lbossard/accv12/
[2]: https://github.com/Cysu/noisy_label
[3]: http://chenlab.ece.cornell.edu/people/Andy/publications/ECCV2012_ClothingAttributes.pdf
[4]: http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html
[5]: https://github.com/switchablenorms/DeepFashion2
[6]: https://vision.cornell.edu/se3/wp-content/uploads/2019/06/1906.05750.pdf
[7]: https://www.kaggle.com/c/imaterialist-fashion-2019-FGVC6
[8]: http://tamaraberg.com/street2shop/
[9]: http://streetstyle.cs.cornell.edu/#dataset
[10]: https://drive.google.com/open?id=1HtPwNgL3_aW7APGgyIIjMcHUQaz3AORz
[11]: http://tamaraberg.com/hipsterwars/
[12]: http://mvc-datasets.github.io/MVC/
[13]: https://github.com/kyamagu/paperdoll
[14]: https://github.com/bearpaw/clothing-co-parsing
[15]: https://github.com/xthan/polyvore-dataset
[16]: https://github.com/eBay/modanet

## 4. Companies

* [Chicisimo](https://hackernoon.com/how-we-grew-from-0-to-4-million-women-on-our-fashion-app-with-a-vertical-machine-learning-approach-f8b7fc0a89d7)
* [infimind](https://www.infimind.com/#)

## Similar Repository

- [Cool Fashion Papers](https://github.com/lzhbrian/Cool-Fashion-Papers)
- [awesome-fashion-ai](https://github.com/ayushidalmia/awesome-fashion-ai)
- [mmfashion](https://github.com/open-mmlab/mmfashion)
- [DATASOURCE for fAshIon](https://github.com/andrewjong/DATASOURCE#2-attribute)

