# FIPNet
Official code of "FIPNet: Self-Supervised Low-Light Image Enhancement Combining Feature and Illumination Priors". (The code will be released following the article accepted)

# Network Architecture
![overall_arc](https://github.com/user-attachments/assets/229c1ce9-3375-49ce-8a22-3562551b0c2b)


# Project Setup
This is a Pytorch implementation of FIPNet.

1、Python 3.9  
2、Pytorch == 1.13.1 cuda == 11.7  
3、TorchVision == 0.14
```
conda create --n cp39_torch1_13_1_vision_0_14_cu117 python=3.9
conda activate cp39_torch1_13_1_vision_0_14_cu117
cd FIPNet
pip install -r requirements.txt
```
# Experiment Result

![qualitative_evaluation](https://github.com/user-attachments/assets/1c27c4fa-60f2-482a-a112-98958d0ee4a9)

# Contributions
If you have any questions/comments/bug reports, feel free to e-mail the author Jie Cao (caojie@s.dlu.edu.cn).
