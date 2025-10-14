<div align=center>

# Representation as Compression: A Survey of Neural Fitting-based Data Compression

</div>

> **Representation as Compression: A Survey of Neural Fitting-based Data Compression** 
> [Youneng Bao](https://github.com/baoyu2020)<sup>1</sup>, [Yiping Liu](https://nouise.github.io/DD-RUO/)<sup>2</sup>, [YuLong Cheng](https://github.com/smileto1/)<sup>2</sup>
> 
> <sup>1</sup>City University of Hong Kong (CityUHK), <sup>2</sup>Harbin Institute of Technology, Shenzhen(HITSZ)
> 


---

> [!IMPORTANT]
> We welcome your help in improving the repository and paper. Please feel free to submit a [pull request](https://github.com/cokeshao/Awesome-Multimodal-Token-Compression/pulls) or [contact us](#️-contact) to:
> 
> - Add a relevant paper not yet included.
>
> - Suggest a more suitable category.
>
> - Update the information.
>
> - Ask for clarification about any content.

---
## 📚 Contents

- [Awesome Token Compression](#awesome-multimodal-token-compression)
    - [INR : 2D Image](https://github.com/cokeshao/Awesome-Multimodal-Token-Compression/tree/main/image-llm.md)
    - [INR : Video](https://github.com/cokeshao/Awesome-Multimodal-Token-Compression/tree/main/video-llm.md)
    - [INR : Audios](https://github.com/cokeshao/Awesome-Multimodal-Token-Compression/tree/main/audio-llm.md)
    - [INR : 3D](https://github.com/cokeshao/Awesome-Multimodal-Token-Compression/tree/main/vision-transformer.md)
    - [INR : 4D](https://github.com/cokeshao/Awesome-Multimodal-Token-Compression/tree/main/audio-transformer.md)
    - [Primitive-Based Representations : 2D Image](https://github.com/cokeshao/Awesome-Multimodal-Token-Compression/tree/main/image-llm.md)
    - [Primitive-Based Representations : Video](https://github.com/cokeshao/Awesome-Multimodal-Token-Compression/tree/main/video-llm.md)
    - [Primitive-Based Representations : 3D](https://github.com/cokeshao/Awesome-Multimodal-Token-Compression/tree/main/vision-transformer.md)
    - [Primitive-Based Representations : 4D](https://github.com/cokeshao/Awesome-Multimodal-Token-Compression/tree/main/audio-transformer.md)
    - [Grid-Based Representations : 3D](https://github.com/cokeshao/Awesome-Multimodal-Token-Compression/tree/main/vision-transformer.md)
    - [Grid-Based Representations : 4D](https://github.com/cokeshao/Awesome-Multimodal-Token-Compression/tree/main/audio-transformer.md)
  
**Please check out all the papers by selecting the sub-area you're interested in. On this main page, only papers released in the past 6 months are shown.**

---

---

## ✅ 二、根据你提供的图，给出对应的 Mermaid 实现

下面是与你图中层次对应的 Mermaid 版本（Functional / Parametric Primitive 两部分）：

```markdown
```mermaid
flowchart TB
    %% 主体标题
    A["Neural Overfitting as Data Compression"]:::main

    %% 一级分支
    A --> B["Functional (§3)"]
    A --> C["Parametric Primitive (§4)"]

    %% Functional 部分
    B --> B1["Audio (§3)"]
    B1 -->|"InternVL1.5"| B1A["InternVL1.5"]

    B --> B2["2D Image (§??)"]
    B2 -->|"InternVL1.5"| B2A["InternVL1.5"]

    B --> B3["Video (§??)"]
    B3 -->|"Token Distillation"| B3A["InstructBLIP [?]"]
    B3 -->|"Cross-Modal Selection"| B3B["SparseVLM [?], AdaFV [?], TRIM [?]"]

    B --> B4["3D Shapes / Volumetric (§??)"]
    B4 -->|"Token Distillation"| B4A["InstructBLIP [?]"]
    B4 -->|"Cross-Modal Selection"| B4B["SparseVLM [?], AdaFV [?], TRIM [?]"]

    B --> B5["Higher Dimension (§??)"]
    B5 -->|"5D/6D Radiance Fields"| B5A["Scene Representation"]
    B5 -->|"General N-Dimensional Functions"| B5B["Scientific Data and Beyond"]

    %% Parametric Primitive 部分
    C --> C1["Audio (§??)"]
    C1 -->|"InternVL1.5"| C1A["InternVL1.5"]

    C --> C2["2D Image (§??)"]
    C2 -->|"InternVL1.5"| C2A["InternVL1.5"]

    C --> C3["Video (§??)"]
    C3 -->|"Token Distillation"| C3A["InstructBLIP [?]"]
    C3 -->|"Cross-Modal Selection"| C3B["SparseVLM [?], AdaFV [?], TRIM [?]"]

    C --> C4["3D Shapes / Volumetric (§??)"]
    C4 -->|"Token Distillation"| C4A["InstructBLIP [?]"]
    C4 -->|"Cross-Modal Selection"| C4B["SparseVLM [?], AdaFV [?], TRIM [?]"]

    C --> C5["Higher Dimension (§??)"]
    C5 -->|"5D/6D Radiance Fields"| C5A["Scene Representation"]
    C5 -->|"General N-Dimensional Functions"| C5B["Scientific Data and Beyond"]

    %% 样式定义
    classDef main fill:#f7f7f7,stroke:#444,stroke-width:1.5px,color:#000,font-weight:bold;
    classDef sub fill:#e0f7f4,stroke:#444,stroke-width:1px;

### Badge Colors
- ![arXiv Badge](https://img.shields.io/badge/arXiv-red) `red` for arXiv papers
- ![PDF Badge](https://img.shields.io/badge/PDF-blue) `blue` for conference/journal papers
- ![GitHub Badge](https://img.shields.io/badge/GitHub-white) `white` for GitHub repositories
- ![Research Areas Badge](https://img.shields.io/badge/Areas-purple) `purple` for research areas
- ![Categories Badge](https://img.shields.io/badge/Categories-green) `green` for categories
- ![Cost Badge](https://img.shields.io/badge/Cost-yellow) `yellow` for training cost

### Recent Papers (Last 6 Months)


<details open>
<summary><strong>(INR)2D Image</strong></summary>

| **Title & Authors** | **Areas** | **Tags** | **Links** | 
| --- | --- | --- | :---: | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[CATP: Contextually Adaptive Token Pruning for Efficient and Enhanced Multimodal In-Context Learning](https://arxiv.org/abs/2508.07871)<br>Yanshu Li, Jianjiang Yang, Zhennan Shen, Ligong Han, Haoyan Xu, Ruixiang Tang |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]() [![Type](https://img.shields.io/badge/Similarity--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.07871)<br> | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[AdaptInfer: Adaptive Token Pruning for Vision-Language Model Inference with Dynamical Text Guidance](https://arxiv.org/abs/2508.06084)<br>Weichen Zhang, Zhui Zhu, Ningbo Li, Kebin Liu, Yunhao Liu |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.06084)<br> | 
</details>

<details open>
<summary><strong>(INR)Video</strong></summary>

| **Title & Authors** | **Areas** | **Tags** | **Links** | 
| --- | --- | --- | :---: | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[CATP: Contextually Adaptive Token Pruning for Efficient and Enhanced Multimodal In-Context Learning](https://arxiv.org/abs/2508.07871)<br>Yanshu Li, Jianjiang Yang, Zhennan Shen, Ligong Han, Haoyan Xu, Ruixiang Tang |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]() [![Type](https://img.shields.io/badge/Similarity--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.07871)<br> | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[AdaptInfer: Adaptive Token Pruning for Vision-Language Model Inference with Dynamical Text Guidance](https://arxiv.org/abs/2508.06084)<br>Weichen Zhang, Zhui Zhu, Ningbo Li, Kebin Liu, Yunhao Liu |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.06084)<br> | 
</details>

<details open>
<summary><strong>(INR)Audios</strong></summary>

| **Title & Authors** | **Areas** | **Tags** | **Links** | 
| --- | --- | --- | :---: | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[CATP: Contextually Adaptive Token Pruning for Efficient and Enhanced Multimodal In-Context Learning](https://arxiv.org/abs/2508.07871)<br>Yanshu Li, Jianjiang Yang, Zhennan Shen, Ligong Han, Haoyan Xu, Ruixiang Tang |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]() [![Type](https://img.shields.io/badge/Similarity--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.07871)<br> | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[AdaptInfer: Adaptive Token Pruning for Vision-Language Model Inference with Dynamical Text Guidance](https://arxiv.org/abs/2508.06084)<br>Weichen Zhang, Zhui Zhu, Ningbo Li, Kebin Liu, Yunhao Liu |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.06084)<br> | 
</details>

<details open>
<summary><strong>(INR)3D</strong></summary>

| **Title & Authors** | **Areas** | **Tags** | **Links** | 
| --- | --- | --- | :---: | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[CATP: Contextually Adaptive Token Pruning for Efficient and Enhanced Multimodal In-Context Learning](https://arxiv.org/abs/2508.07871)<br>Yanshu Li, Jianjiang Yang, Zhennan Shen, Ligong Han, Haoyan Xu, Ruixiang Tang |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]() [![Type](https://img.shields.io/badge/Similarity--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.07871)<br> | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[AdaptInfer: Adaptive Token Pruning for Vision-Language Model Inference with Dynamical Text Guidance](https://arxiv.org/abs/2508.06084)<br>Weichen Zhang, Zhui Zhu, Ningbo Li, Kebin Liu, Yunhao Liu |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.06084)<br> | 
</details>

<details open>
<summary><strong>(INR)4D</strong></summary>

| **Title & Authors** | **Areas** | **Tags** | **Links** | 
| --- | --- | --- | :---: | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[CATP: Contextually Adaptive Token Pruning for Efficient and Enhanced Multimodal In-Context Learning](https://arxiv.org/abs/2508.07871)<br>Yanshu Li, Jianjiang Yang, Zhennan Shen, Ligong Han, Haoyan Xu, Ruixiang Tang |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]() [![Type](https://img.shields.io/badge/Similarity--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.07871)<br> | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[AdaptInfer: Adaptive Token Pruning for Vision-Language Model Inference with Dynamical Text Guidance](https://arxiv.org/abs/2508.06084)<br>Weichen Zhang, Zhui Zhu, Ningbo Li, Kebin Liu, Yunhao Liu |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.06084)<br> | 
</details>

<details open>
<summary><strong>(Primitive-Based Representations)2D Image</strong></summary>

| **Title & Authors** | **Areas** | **Tags** | **Links** | 
| --- | --- | --- | :---: | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[CATP: Contextually Adaptive Token Pruning for Efficient and Enhanced Multimodal In-Context Learning](https://arxiv.org/abs/2508.07871)<br>Yanshu Li, Jianjiang Yang, Zhennan Shen, Ligong Han, Haoyan Xu, Ruixiang Tang |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]() [![Type](https://img.shields.io/badge/Similarity--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.07871)<br> | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[AdaptInfer: Adaptive Token Pruning for Vision-Language Model Inference with Dynamical Text Guidance](https://arxiv.org/abs/2508.06084)<br>Weichen Zhang, Zhui Zhu, Ningbo Li, Kebin Liu, Yunhao Liu |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.06084)<br> | 
</details>



<details open>
<summary><strong>(Primitive-Based Representations)Video</strong></summary>

| **Title & Authors** | **Areas** | **Tags** | **Links** | 
| --- | --- | --- | :---: | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[CATP: Contextually Adaptive Token Pruning for Efficient and Enhanced Multimodal In-Context Learning](https://arxiv.org/abs/2508.07871)<br>Yanshu Li, Jianjiang Yang, Zhennan Shen, Ligong Han, Haoyan Xu, Ruixiang Tang |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]() [![Type](https://img.shields.io/badge/Similarity--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.07871)<br> | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[AdaptInfer: Adaptive Token Pruning for Vision-Language Model Inference with Dynamical Text Guidance](https://arxiv.org/abs/2508.06084)<br>Weichen Zhang, Zhui Zhu, Ningbo Li, Kebin Liu, Yunhao Liu |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.06084)<br> | 
</details>

<details open>
<summary><strong>(Primitive-Based Representations)3D</strong></summary>

| **Title & Authors** | **Areas** | **Tags** | **Links** | 
| --- | --- | --- | :---: | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[CATP: Contextually Adaptive Token Pruning for Efficient and Enhanced Multimodal In-Context Learning](https://arxiv.org/abs/2508.07871)<br>Yanshu Li, Jianjiang Yang, Zhennan Shen, Ligong Han, Haoyan Xu, Ruixiang Tang |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]() [![Type](https://img.shields.io/badge/Similarity--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.07871)<br> | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[AdaptInfer: Adaptive Token Pruning for Vision-Language Model Inference with Dynamical Text Guidance](https://arxiv.org/abs/2508.06084)<br>Weichen Zhang, Zhui Zhu, Ningbo Li, Kebin Liu, Yunhao Liu |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.06084)<br> | 
</details>


<details open>
<summary><strong>(Primitive-Based Representations)4D</strong></summary>

| **Title & Authors** | **Areas** | **Tags** | **Links** | 
| --- | --- | --- | :---: | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[CATP: Contextually Adaptive Token Pruning for Efficient and Enhanced Multimodal In-Context Learning](https://arxiv.org/abs/2508.07871)<br>Yanshu Li, Jianjiang Yang, Zhennan Shen, Ligong Han, Haoyan Xu, Ruixiang Tang |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]() [![Type](https://img.shields.io/badge/Similarity--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.07871)<br> | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[AdaptInfer: Adaptive Token Pruning for Vision-Language Model Inference with Dynamical Text Guidance](https://arxiv.org/abs/2508.06084)<br>Weichen Zhang, Zhui Zhu, Ningbo Li, Kebin Liu, Yunhao Liu |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.06084)<br> | 
</details>

<details open>
<summary><strong>(Grid-Based Representation)3D</strong></summary>

| **Title & Authors** | **Areas** | **Tags** | **Links** | 
| --- | --- | --- | :---: | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[CATP: Contextually Adaptive Token Pruning for Efficient and Enhanced Multimodal In-Context Learning](https://arxiv.org/abs/2508.07871)<br>Yanshu Li, Jianjiang Yang, Zhennan Shen, Ligong Han, Haoyan Xu, Ruixiang Tang |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]() [![Type](https://img.shields.io/badge/Similarity--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.07871)<br> | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[AdaptInfer: Adaptive Token Pruning for Vision-Language Model Inference with Dynamical Text Guidance](https://arxiv.org/abs/2508.06084)<br>Weichen Zhang, Zhui Zhu, Ningbo Li, Kebin Liu, Yunhao Liu |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.06084)<br> | 
</details>

<details open>
<summary><strong>(Grid-Based Representation)4D</strong></summary>

| **Title & Authors** | **Areas** | **Tags** | **Links** | 
| --- | --- | --- | :---: | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[CATP: Contextually Adaptive Token Pruning for Efficient and Enhanced Multimodal In-Context Learning](https://arxiv.org/abs/2508.07871)<br>Yanshu Li, Jianjiang Yang, Zhennan Shen, Ligong Han, Haoyan Xu, Ruixiang Tang |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]() [![Type](https://img.shields.io/badge/Similarity--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.07871)<br> | 
|  [![Arxiv](https://img.shields.io/badge/arXiv-2025\.08-red)]() <br>[AdaptInfer: Adaptive Token Pruning for Vision-Language Model Inference with Dynamical Text Guidance](https://arxiv.org/abs/2508.06084)<br>Weichen Zhang, Zhui Zhu, Ningbo Li, Kebin Liu, Yunhao Liu |  [![Area](https://img.shields.io/badge/Image--LLM-purple)]() |  [![Type](https://img.shields.io/badge/Attention--Based-green)]()<br> [![Cost](https://img.shields.io/badge/Training--Free-yellow)]() |  [Paper](https://arxiv.org/abs/2508.06084)<br> | 
</details>
