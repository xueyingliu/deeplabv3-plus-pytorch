## DeepLabv3+：Encoder-Decoder with Atrous Separable Convolution语义分割模型在Pytorch当中的实现
---

## 导出onnx环境
onnx                      1.14.0  
onnxruntime-gpu           1.15.1  
torch                     1.11.0+cu113  
torchvision               0.12.0+cu113  
mmcv-full                 1.7.1  
timm                      0.9.2  

## inference
```
python predict.py

```

## Evaluation

```
python get_miou_onnx.py

```
