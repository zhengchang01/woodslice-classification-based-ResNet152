
## testing environment
```
pip install -r requirements.txt
```


Before running the code, you should download the weight([Baidupan](https://pan.baidu.com/s/1LkraQvGkAs_ZaHew7hXQ6w)) file. And put this file in logs/cut1800. 
Extracted code:0ma0

## Running this code
```
python tools/single_test.py "your img path" "your model path"
```
Note that you will need a local copy of ImageNet compatible with the TFDS format
used in dataset.py in order to train on ImageNet.

