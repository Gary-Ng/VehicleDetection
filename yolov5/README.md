<p>
This YOLOv5 🚀 is creating using custom dataset and trained on yolov5s.
</p>


## <div align="center">Documentation</div>

All files that are required to run the models are included in the repo, excluding most of the dataset. All commands will be provided below to run the inference.

## <div align="center">Quick Start Examples</div>

<details open>
<summary>Install</summary>

Clone repo and install [requirements.txt](https://github.com/ultralytics/yolov5/blob/master/requirements.txt) in a
[**Python>=3.7.0**](https://www.python.org/) environment, including
[**PyTorch>=1.7**](https://pytorch.org/get-started/locally/).

```bash
clone this repo  # clone
cd yolov5
pip install -r requirements.txt  # install
```

</details>

<details open>
<summary>Training Of Custom Model</summary>


```python

python train.py --img 416 --batch 16 --epochs 1 --data ../datasets/Vehicle-Detection-1/data.yaml --weights runs/train/exp/weights/best.pt --cache
```

</details>



<details open>
<summary>Inference with detect.py</summary>

```bash
Inferencing of images
python detect.py --weights runs/train/exp/weights/best.pt --img 416 --source ../datasets/Vehicles-Detection-1/test/images
   
Inferencing of youtube videos [pafy and youtube_dl dependencies needed] 
python detect.py --weights runs/train/exp/weights/best.pt --img 416 --source {insert link of youtube video}
   
Inferencing and download of video locally
python detect.py --weights runs/train/exp/weights/best.pt --img 416 --source {path to video}
```

</details>


<details open>
   <summary> Gif of result </summary>
   
   ![GIF](https://github.com/Gary-Ng/VehicleDetection/blob/main/yolov5/yolov5/images/yolov5.gif)
   </details>
   
</details>

<details open>
   <summary> Validation of Model </summary>
   
   python val.py --weights runs/train/exp/weights/best.pt --data ../datasets/Vehicle-Detection-1/data.yaml --img 640 --iou 0.6 --half
   
   ![PR_curve](https://github.com/Gary-Ng/VehicleDetection/blob/main/yolov5/yolov5/runs/val/exp/PR_curve.png)
 </details>

<details>
   <summary>fps image</summary>
    ![fps](https://github.com/Gary-Ng/VehicleDetection/blob/main/yolov5/yolov5/images/yolov5_fps.JPG)

</details>
<details>
<summary> Contribution and Credits </summary>
## <div align="center">Contribute</div>

We love your input! We want to make contributing to YOLOv5 as easy and transparent as possible. Please see our [Contributing Guide](CONTRIBUTING.md) to get started, and fill out the [YOLOv5 Survey](https://ultralytics.com/survey?utm_source=github&utm_medium=social&utm_campaign=Survey) to send us feedback on your experiences. Thank you to all our contributors!

<a href="https://github.com/ultralytics/yolov5/graphs/contributors"><img src="https://opencollective.com/ultralytics/contributors.svg?width=990" /></a>

## <div align="center">Contact</div>

For YOLOv5 bugs and feature requests please visit [GitHub Issues](https://github.com/ultralytics/yolov5/issues). For business inquiries or
professional support requests please visit [https://ultralytics.com/contact](https://ultralytics.com/contact).

<br>

<div align="center">
    <a href="https://github.com/ultralytics">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-github.png" width="3%"/>
    </a>
    <img width="3%" />
    <a href="https://www.linkedin.com/company/ultralytics">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-linkedin.png" width="3%"/>
    </a>
    <img width="3%" />
    <a href="https://twitter.com/ultralytics">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-twitter.png" width="3%"/>
    </a>
    <img width="3%" />
    <a href="https://www.producthunt.com/@glenn_jocher">
    <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-producthunt.png" width="3%"/>
    </a>
    <img width="3%" />
    <a href="https://youtube.com/ultralytics">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-youtube.png" width="3%"/>
    </a>
    <img width="3%" />
    <a href="https://www.facebook.com/ultralytics">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-facebook.png" width="3%"/>
    </a>
    <img width="3%" />
    <a href="https://www.instagram.com/ultralytics/">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-instagram.png" width="3%"/>
    </a>
</div>
</details>
