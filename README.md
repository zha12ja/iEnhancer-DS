# iEnhancer-DS

iEnhancer-DS: Attention-Based improved DenseNet for identifying enhancers and their strengths

![image](https://github.com/user-attachments/assets/f2076ffe-237e-4d51-9305-f34bce00852e)

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

#### 2.1 Task 1: Enhancer identification

Use "First_task.py" to identify enhancers

```
python First_task.py
```

#### 2.2 Task 1: Enhancer identification

Use "Second_task.py" to identify enhancers strength

```
python Second_task.py
```

