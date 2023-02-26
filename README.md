# Custom-Object-Detection
Step by step how to create object detection using Tensorflow 2

> note: this tutorial is tested on windows 11 on anaconda3 environment

# 1. install anaconda

> in order to install anaconda3 just klik in this [link](https://repo.anaconda.com/archive/Anaconda3-2022.10-Windows-x86_64.exe)

> or visit to anaconda official website
https://www.anaconda.com/products/distribution
![My Image](https://github.com/candjaya123/Asset/blob/main/images/anaconda.png)

# 2. create new environment

#### first open Anaconda Prompt and run the command below to create new environment
![My Image](https://github.com/candjaya123/Asset/blob/main/images/Screenshot_20230227_010606.png)
    
```
conda create -n [env_name] pip python=3.9 
conda activate [env_name]
```

# 3. installing package on conda

```
conda install ipykernel
conda install jupyter
conda install protobuf
conda install matplotlib
```

# 4. clone repository

```
git clone https://github.com/candjaya123/Custom-Object-Detection.git

```

# 5. collect images dataset

### get inside clone repo and type command on Anaconda Prompt

```
jupyter notebook

```
### ![My Image](https://github.com/candjaya123/Asset/blob/main/images/Screenshot_20230227_003840.png)

> just run all shell inside Collect_Image.ipynb

### on step labeling image
### ![My Image](https://github.com/candjaya123/Asset/blob/main/images/Screenshot_20230227_005057.png)

### select the folder name to open dir and save dir exactly same as label defined before on this step

### ![My Image](https://github.com/candjaya123/Asset/blob/main/images/Screenshot_20230227_005541.png)

### ![My Image](https://github.com/candjaya123/Asset/blob/main/images/Screenshot_20230227_004927.png)

### use this usefull short cut to create label images

```
Ctrl + w to add bounding box
Ctrl + a to move on images before
Ctrl + d to move on next images
Ctrl + c to copy boxes
Ctrl + v to paste boxes

```

# 6. train model

### ![My Image](https://github.com/candjaya123/Asset/blob/main/images/Screenshot_20230227_003840.png)

> just run all shell inside Training.ipynb
