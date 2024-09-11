# LTCD
Pytorch codes of **Adapting Vision Foundation Models with Lightweight Trident Decoder for Remote Sensing Change Detection** 

The complete code will be released after the paper is accepted.

The LTCD adopts [FastSAM](https://github.com/CASIA-IVA-Lab/FastSAM) as the visual encoder with some modifications.


## How to Use

1. Inference and evaluation
   
   inference on test sets: set the chkpt_path and run
   
   `python pred_CD.py`
   
   evaluation of accuracy: set the prediction dir and GT dir, and run
   
   `python eval_CD.py`
   
   

## Dataset Download

In the following, we summarize links to some frequently used CD datasets:

* [LEVIR-CD](https://justchenhao.github.io/LEVIR/)
* [WHU-CD](https://study.rsgis.whu.edu.cn/pages/download/) [(baidu)](https://pan.baidu.com/s/1A0_xbV4ZktWCbL3j94CInA?pwd=WHCD )
* [CLCD (Baidu)](https://pan.baidu.com/s/1iZtAq-2_vdqoz1RnRtivng?pwd=CLCD)
* [S2Looking](https://github.com/S2Looking/Dataset)
* [SYSU-CD](https://github.com/liumency/SYSU-CD)

## Pretrained Models

For readers to easily evaluate the accuracy, we provide the trained weights of the LTCD.
[Baidu](链接: https://pan.baidu.com/s/1yTjBrW2SxxA91CSE1KejoQ) (pswd: o6d2)

## Predict Results
For readers to easily evaluate the accuracy, we also provide the predict results of the LTCD.
[Baidu](https://pan.baidu.com/s/1OrmvRXB3l4ogJSU2kJ1E_w) (pswd: iigk)
## Cite LTCD


