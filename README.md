# HyperNet

## Install

```
conda activate -n hypernet python=3.8
conda activate hypernet
pip install -r requirements.txt
```

## Dataset

Please download the datasets from the official website and split them yourself.

Vaihingen

Postdam

LoveDA

## Training

```
python HyperNet/train_supervision.py -c HyperNet/config/vaihingen/hypernet.py
```


## Testing

```
python vaihingen_test.py -c HyperNet/config/vaihingen/hypernet.py -o fig_results/vaihingen/hypernet-test --rgb -t lr
```
