# GLTScene
The code for our paper [GLTScene: Global‐to‐Local Transformers for Indoor Scene Synthesis with General Room Boundaries](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.15236) (PG 2024).

We present GLTScene, a novel data-driven method for high-quality furniture layout synthesis with general room boundaries as conditions. This task is challenging since the existing indoor scene datasets do not cover the variety of general room boundaries. We incorporate the interior design principles with learning techniques and adopt a global-to-local strategy for this task. Globally, we learn the placement of furniture objects from the datasets without considering their alignment. Locally, we learn the alignment of furniture objects relative to their nearest walls, according to the alignment principle in interior design. The global placement and local alignment of furniture objects are achieved by two transformers respectively. We compare our method with several baselines in the task of furniture layout synthesis with general room boundaries as conditions. Our method outperforms these baselines both quantitatively and qualitatively. We also demonstrate that our method can achieve other conditional layout synthesis tasks, including object-level conditional generation and attribute-level conditional generation.

![teaser](README.assets/teaser.png)

# Installation & Dependencies

The dependencies of our code have been recorded in `environment. yaml`.

You can create a conda environment called `GLTScene` using

```
conda env create -f environment.yaml
```

# Dataset 

We used the [3D-FRONT](https://tianchi.aliyun.com/specials/promotion/alibaba-3d-scene-dataset) and the [3D-FUTURE](https://tianchi.aliyun.com/specials/promotion/alibaba-3d-future) dataset to train our model. To download both datasets, please follow the guidelines outlined on the dataset's [webpage](https://tianchi.aliyun.com/specials/promotion/alibaba-3d-scene-dataset).

# Data Preprocessing

Coming soon.

# Usage

## Training

## Inference

# Citation

If you find this useful for your research, please consider citing:

```
@inproceedings{li2024gltscene,
  title={GLTScene: Global-to-Local Transformers for Indoor Scene Synthesis with General Room Boundaries},
  author={Li, Yijie and Xu, Pengfei and Ren, Junquan and Shao, Zefan and Huang, Hui},
  booktitle={Computer Graphics Forum},
  pages={e15236},
  year={2024},
  organization={Wiley Online Library}
}
```

