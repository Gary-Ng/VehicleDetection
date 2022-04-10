# VehicleDetection


<p>
YOLOv5 🚀 
</p>

<details open>
   <summary> Gif of Yolov5 </summary>
   
   ![GIF](https://github.com/Gary-Ng/VehicleDetection/blob/main/yolov5/yolov5/images/yolov5.gif)
   
</details>

<details open>
   <summary> Validation of Model </summary>
   
   python val.py --weights runs/train/exp/weights/best.pt --data ../datasets/Vehicle-Detection-1/data.yaml --img 640 --iou 0.6 --half
   
   ![PR_curve](https://github.com/Gary-Ng/VehicleDetection/blob/main/yolov5/yolov5/runs/val/exp/PR_curve.png)
 </details>

<details open>
   <summary> Yolov5 FPS </summary>
   
   ![](https://github.com/Gary-Ng/VehicleDetection/blob/main/yolov5/yolov5/images/yolov5-fps.jpg)
   
</details>

<p>
  SSD TFLite
  </p>
<details open>
   <summary> Gif SSD </summary>
   
   ![GIF](https://github.com/Gary-Ng/VehicleDetection/blob/main/ssd_tflite/ssd_tflite_result.gif)
   
</details>


<details open>
   <summary> Validation of Model </summary>
   
   ![Recall](https://github.com/Gary-Ng/VehicleDetection/blob/main/ssd_tflite/ssd_recall.jpg)
   
   ![mAP](https://github.com/Gary-Ng/VehicleDetection/blob/main/ssd_tflite/ssd_mAP.jpg)
 </details>

<details open>
   <summary> Yolov5 FPS </summary>
   
   ![](https://github.com/Gary-Ng/VehicleDetection/blob/main/yolov5/yolov5/images/yolov5-fps.jpg)
   
</details>
