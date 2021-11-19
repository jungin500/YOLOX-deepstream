# YOLOX(Megvii-BaseDetection) Deploy DeepStream V2

This project base on https://github.com/Megvii-BaseDetection/YOLOX  and https://zhuanlan.zhihu.com/p/391693130


# News

Deploy yolox to deep stream, FPS > 70 - 2021-7-21

# System Requirements
- CUDA 10.2+ (Supports Jetson series)
- TensorRT 7.X+
- OpenCV 4.0+ (with/without `contrib` modules)
- OpenMP
- DeepStream 5.x/6.0

# Installation
```bash
git clone https://github.com/jungin500/YOLOX-deepstream

cd YOLOX-deepstream
make
```

use to parse infer postprocess.

# Run

```shell
cd YOLOX-deepstream
deepstream-app -c deepstream_app_config.txt
```

# How to build engine?
https://zhuanlan.zhihu.com/p/391693130

# License
- following [original repository](https://github.com/nanmi/YOLOX-deepstream/)