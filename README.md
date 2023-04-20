# StAGN
StAGN: Spatial-Temporal Adaptive Graph Network via Constranstive Learning for Sleep Stage Classification, which is improved from [MSTGCN](https://github.com/ziyujia/MSTGCN).

![model_architecture](model_structure.jpg)

## Citation

If you find this useful, please cite our work as follows:

```latex
@inproceedings{chen2023stagn,
  title={StAGN: Spatial-Temporal Adaptive Graph Network via Contrastive Learning for Sleep Stage Classification},
  author={Chen, Junyang and Dai, Yidan and Chen, Xianhui and Shen, Yingshan and Luximon, Yan and Wang, Hailiang and He, Yuxin and Ma, Wenjun and Fan, Xiaomao},
  booktitle={Proceedings of the 2023 SIAM International Conference on Data Mining (SDM)},
  pages={199--207},
  year={2023},
  organization={SIAM}
}
```

## Dataset
The ISRUC dataset can be downloaded from website: https://sleeptight.isr.uc.pt

## Preprocess
Run `preprocess.py`

`python preprocess.py`

## Train model
You can change the input data **path** and run. Note that the output from MFE is the STA_GCN's input.
