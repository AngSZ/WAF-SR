# Weight Adjustment Framework for Self-Attention Sequential Recommendation

Our code is built on [AC-TSR](https://github.com/AIM-SE/AC-TSR). Relevant materials are being sorted out.

# Preparation

> * torch==1.11.0
> * numpy==1.19.2
> * einops==0.6.1
> * tensorboard==2.11.2

# Usage

* Download datasets from  [Google Drive](https://drive.google.com/drive/folders/1ahiLmzU7cGRPXf5qGMqtAChte2eYp9gI). And put the files in ./dataset/ like the following.

```
$ tree
.
├── Amazon_Beauty
│   ├── Amazon_Beauty.inter
│   └── Amazon_Beauty.item
├── Amazon_Toys_and_Games
│   ├── Amazon_Toys_and_Games.inter
│   └── Amazon_Toys_and_Games.item
└── yelp
    ├── README.md
    ├── yelp.inter
    ├── yelp.item
    └── yelp.user
```

* run the following command to run WAF-SR on a specific dataset.

```
bash scripts/run.sh amazon-beauty
```
# Acknowledgements
This repository is based on [Recbole](https://github.com/RUCAIBox/RecBole) and [AC-TSR](https://github.com/AIM-SE/AC-TSR).
