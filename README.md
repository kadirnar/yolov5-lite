<div align="center">
<h1>
  Yolov5-StrongSort: YOLOv5-Pip + StrongSort
</h1>

<h4>
    <img width="700" alt="teaser" src="resources/uav.gif">
</h4>
</div>

## <div align="center">Overview</div>

This repo is a shortened version of yolov5 codes and added deep sort algorithm.

### Installation

```
git clone https://github.com/kadirnar/yolov5-strongsort
cd yolov5-strongsort
pip install -r requirements.txt
```

### Yolov5 Model + StrongSort Prediction

```
python detect.py --source test.mp4 --yolo_model yolov5x6.pt --deep_sort_model osnet_x1_0 --show-vid
```


## Citations
```bibtex
@misc{yolov5-strongsort-osnet-2022,
    title={Real-time multi-camera multi-object tracker using YOLOv5 and StrongSORT with OSNet},
    author={Mikel Broström},
    howpublished = {\url{https://github.com/mikel-brostrom/Yolov5_StrongSORT_OSNet}},
    year={2022}
}
```
### Reference:

 - [YOLOv5](https://github.com/ultralytics/yolov5)
 - [StrongSORT_OSNet](https://github.com/mikel-brostrom/Yolov5_StrongSORT_OSNet)
