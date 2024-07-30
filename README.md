# Train model with custom dataset
<a href="https://colab.research.google.com/drive/1P2m1-RMC5hZZvLiysjP2TLW07W8qhqHv?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

**Dataset**
```bash
├── Dataset
    └── train_image ──├── image1.jpg
    │                 └── image1.lines.txt
    │                 ├── ...
    │                 └── ...
    └── list
    │    └── ├── train.txt
    │        └── train_gt.txt
    │        ├── val.txt
    │        └── test.txt
    │
    └── laneseg_label_w16
         └── train_image ──├── image1.png
                           └── ...
```

**You can create ```laneseg_label_w16``` and ```train_gt.txt``` in <a href="https://github.com/XingangPan/seg_label_generate">here</a>**
