# Real-Times Glove Detection via Lightweight YOLOv3 with Enhanced Attention and Efficient IoU Loss
> Accurate and real-time glove detection is crucial for safeguarding worker safety in industrial environments. In this study, we present an enhanced glove detection network built upon a lightweight YOLOv3 architecture, incorporating a Convolutional Block Attention Module (CBAM) and the Efficient Intersection over Union (EIoU) loss function. These improvements resulted in significant gains, with a 3.4% increase in mAP50 and a 15.5% increase in mAP95, alongside a 30.9% acceleration in inference speed, a 54.65% reduction in parameters, and a 60.85% decrease in GFLOPS. Our method demonstrates improved efficiency and accuracy in real-time glove detection, contributing significantly to enhancing worker safety in industrial settings. The proposed approach was evaluated on a self-built glove dataset, outperforming several state-of-the-art object detection models.

## <div align="center">Performance</div>



## <div align="center">Install</div>
克隆 repo，并要求在 [**Python>=3.7.0**](https://www.python.org/) 环境中安装 [requirements.txt](https://github.com/ultralytics/yolov5/blob/master/requirements.txt) ，且要求 [**PyTorch>=1.7**](https://pytorch.org/get-started/locally/) 。

```bash
git clone https://github.com/WMShuai/gloves-yolov3  # clone
cd gloves-yolov3
pip install -r requirements.txt  # install
```
