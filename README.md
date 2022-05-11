# AMR-Dialogue-Project
This is the code base of group 8.

Our project is based on a implementation for paper "Semantic Representation for Dialogue Modeling".
You may find the paper [here](https://arxiv.org/pdf/2105.10188).

# Requirements
+ python 3.6
+ pytorch 1.6

We recommend to use conda to manage virtual environments:
```
conda create --name <env> --file requirements.txt
```
# Data 
The preprocessed data for DialogRE and DialogRG are avaliable at [here](https://drive.google.com/drive/folders/1UEzGAmV5b7POtlH8sH-rDA0GfXlwteDE?usp=sharing) and [here](https://drive.google.com/file/d/1BciSzIKqezfcxgI3CBWk4Qg_FPCheFpz/view?usp=sharing), respectively.

# Preprocessing
```
bash /path/to/code/preprocess.sh
```

# Training
```
bash /path/to/code/run-dual(hier).sh
```

# Evaluation
```
bash /path/to/code/eval.sh                   # for dialogue relation extraction
bash /path/to/code/decode.sh                 # for dialogue response generation
```

# References
```
@inproceedings{bai-etal-2021-semantic,
    title = "Semantic Representation for Dialogue Modeling",
    author = "Bai, Xuefeng  and
      Chen, Yulong  and
      Song, Linfeng  and
      Zhang, Yue",
    booktitle = "Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)",
    month = aug,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.acl-long.342",
    doi = "10.18653/v1/2021.acl-long.342",
    pages = "4430--4445"
}
```
