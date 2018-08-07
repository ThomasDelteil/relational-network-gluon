# relational network with Gluon

---

Gluon inplement of [A simple neural module for relational reasoning](https://arxiv.org/abs/1706.01427)


## Requirements
- Python 3.6.1
- Mxnet(1.2)
- tqdm
- opencv-python


## Usage

- arguments
  - batch_size : Define batch size (defualt=64)
  - epoches : Define total epoches (default=50)
  - GPU_COUNT : Use GPU count (default=2)
  - show_status : show loss and accuracy for each epoch (default=True)

###### data generation
```
python sort-of-clevr.py
``` 

###### default setting
```
python main.py
``` 
or

###### manual setting
```
python main.py --batch_size=32 --epoches=100
```

## Results


## Reference
- https://github.com/kimhc6028/relational-networks
