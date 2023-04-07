# YOLOv5环境配置
## 安装anaconda环境
首先需要安装anaconda的python环境，它可以在做不同项目的时候，可以使用不同的python环境，灵活性很高，必须得配置，一下是安装anaconda的方法

## 配置yolov5环境
### 安装pytorch
如果你没有显卡，那么请安装cpu版本的pytorch
```
conda install pytorch torchvision torchaudio cpuonly -c pytorch
```
如果你有显卡，那么请安装gpu版本的pytorch，gpu版本的torch有加速的效果
首先需要安装cuda和cudnn
首先到myyolov5的路径
