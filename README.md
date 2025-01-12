## Toward Realistic Camouflaged Object Detection: Benchmarks and Method

<img src="RCOD.png"/>


## Dataset Link
Google:https://drive.google.com/drive/folders/1SafBDHRbutQ4D3yqDPOEmZY2u9Ip7Feh

Baidu: https://pan.baidu.com/s/11m8pSerp4hR6pMZMD7WiyQ?pwd=93yd    Extract Code: 93yd 

## Framework install

Our code is based on MMDetection. Here, for the convenience of readers, we have uploaded the full code of mmdetection and our code. If the relevant environment for mmdetection is configured on your server, you can download and use it directly.
MMDetection is an open source object detection toolbox based on PyTorch. We adopt MMDetection as our baseline framework from https://github.com/open-mmlab/mmdetection


**Our environmental installation**
* Linux with Python >= 3.10
* conda create -n RCOD python==3.10
* conda activate RCOD
* [PyTorch](https://pytorch.org/get-started/locally/) >= 2.1.1 & [torchvision](https://github.com/pytorch/vision/) that matches the PyTorch version.
* Our CUDA is 11.8
* Install PyTorch 2.1.1 with CUDA 11.8 
  ```shell
  conda install pytorch==2.1.1 torchvision==0.16.1 torchaudio==2.1.1 pytorch-cuda=11.8 -c pytorch -c nvidia
  ```
* pip install mmcv>=2.2.0
* pip install -r requirements/build.txt
* pip install -v -e . 



<details open>
<summary>Major features</summary>

- **Modular Design**


## Citation

If you use this toolbox or benchmark in your research, please cite this project.

```
@article{mmdetection,
  title   = {{MMDetection}: Open MMLab Detection Toolbox and Benchmark},
  author  = {Chen, Kai and Wang, Jiaqi and Pang, Jiangmiao and Cao, Yuhang and
             Xiong, Yu and Li, Xiaoxiao and Sun, Shuyang and Feng, Wansen and
             Liu, Ziwei and Xu, Jiarui and Zhang, Zheng and Cheng, Dazhi and
             Zhu, Chenchen and Cheng, Tianheng and Zhao, Qijie and Li, Buyu and
             Lu, Xin and Zhu, Rui and Wu, Yue and Dai, Jifeng and Wang, Jingdong
             and Shi, Jianping and Ouyang, Wanli and Loy, Chen Change and Lin, Dahua},
  journal= {arXiv preprint arXiv:1906.07155},
  year={2019}
}
```


