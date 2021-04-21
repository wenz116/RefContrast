# Understanding Synonymous Referring Expressions via Contrastive Features

PyTorch implementation of our method for localizing the object in an image specified by a natural language description.

Contact: Yi-Wen Chen (ychen319@ucmerced.edu)

## Introduction

Referring expression comprehension aims to localize objects identified by natural language descriptions. One nature is that each object can be described by synonymous sentences with paraphrases, and such varieties in languages have critical impact on learning a comprehension model.

While prior work usually treats each sentence and attends it to an object separately, we focus on learning a referring expression comprehension model that considers the property in **synonymous sentences**. To this end, we develop an end-to-end trainable framework to learn **contrastive features** on the image and object instance levels, where features extracted from synonymous sentences to describe the same object should be closer to each other after mapping to the visual domain.

We demonstrate that our method performs favorably against the state-of-the-art approaches on several benchmark datasets. Furthermore, since the varieties in expressions become larger across datasets when they describe objects in different ways, we present the **cross-dataset** and **transfer learning** settings to validate the ability of our learned transferable features.

<p align="center">
<img src="https://github.com/wenz116/RefContrast/blob/main/figure/overview.png" width="75%">
</p>

## Paper

Understanding Synonymous Referring Expressions via Contrastive Features <br />
[Yi-Wen Chen](https://wenz116.github.io/), [Yi-Hsuan Tsai](https://sites.google.com/site/yihsuantsai/home), and [Ming-Hsuan Yang](http://faculty.ucmerced.edu/mhyang/index.html) <br />
*ArXiv pre-print*, 2021 <br />

Please cite our paper if you find it useful for your research.

```
@inproceedings{Chen_RefContrast_2021,
  author = {Yi-Wen Chen and Yi-Hsuan Tsai and Ming-Hsuan Yang},
  journal = {arXiv preprint arXiv:2104.10156},
  title = {Understanding Synonymous Referring Expressions via Contrastive Features},
  year = {2021}
}
```

Codes will be released soon.
