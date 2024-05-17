# 🏥 Meta_Doctor ✔️ 
> Learning deploy Large Medical Model 
## 1. Take XrayGLM as a example for learning.

## 2. Record the install process.
### 2.1 Environment
+ Follow the requirements.txt and environment.yaml
+ Take Special Notice!
  +  Use `python 3.9` is suitable, I encountered a lot of problem in `python 3.11 or 3.10`
### 2.2 Some approaches for error encountered.
+ The first one
  + When in `torch=2.2 or 2.1` appeared `error: (*bias): last dimension must be contiguous`
  + Solving by
    ```python
    pip uninstall torch torchvision & pip install torch==2.0 torchvision```
+ The second one
  + The version of `SwissArmyTransformer` and `Transformers` version should match
  + I use `SwissArmyTransformer=0.4.0` and `Transformers=4.22.3`
## 3. Last demo(merely modify the style)
![efd7b18c2eac7fb5cc74c560af0eaad](https://github.com/lililuya/Meta_Doctor/assets/141640497/a75fe63e-5043-4323-9d3b-9edb6d86dbdd)

## 4. Thinking...
### 4.1 Give it a try to build a meta doctor, go through this pipeline.
+ How to build the pipeline?
  + Input
    + text/audio +image?
  + Output
    + text + image + audio --> video?
