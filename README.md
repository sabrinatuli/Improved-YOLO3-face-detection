# YOLO3-face-detection
Deep learning based face detection
## Introduction

This is a real-time face detection model using YOLOv3 with Keras. 

The YOLOv3 in Keras was done by [qqweee](https://github.com/qqwweee/keras-yolo3). <br />
Face dataset from [WIDER Face](http://shuoyang1213.me/WIDERFACE/)

---

## Quick Start

1. Download YOLOv3-Face model from [HERE](https://drive.google.com/file/d/1zU_n5CwnGfYgFNLQ1JZlsl-rHjPV-kmp/view?usp=sharing)
2. Place `wider_face_yolo.h5` into `model_data/`
3. Run YOLO detection.

```
python yolo_video.py [OPTIONS...] --image, for image detection mode, OR
python yolo_video.py [video_path] [output_path (optional)]
```

### Usage
Use --help to see usage of yolo_video.py:
