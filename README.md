# iEnhancer-DS

iEnhancer-DS: Attention-Based improved DenseNet for identifying enhancers and their strengths

![Model](https://github.com/user-attachments/assets/9afd3ecc-c932-4e97-8bfe-771fda94553d)


## 1.Environment setup

   We recommend you to build a python virtual environment with [Anaconda](https://docs.anaconda.com/anaconda/install/linux/).

#### 1.1 Create and activate a new virtual environment

```
conda create -n ienhancer_ds python=3.6
conda activate ienhancer_ds
```

#### 1.2 Install the package and other requirements

```
python -m pip install -r requirements.txt
```

## 2.Model training

#### 2.1 Task 1: Enhancers identification

Use "First_task.py" to identify enhancers.

```
python First_task.py
```

#### 2.2 Task 2: Enhancers strength prediction

Use "Second_task.py" to prediction enhancers strength.

```
python Second_task.py
```

