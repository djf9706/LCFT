# LCFT
This is a pytorch implementation of the paper 

## Environment Requirement
The code has been tested running under Python 3.8.10 The required packages are as follows:

accelerate
appdirs
loralib
bitsandbytes
black
black[jupyter]
datasets
fire
peft
transformers>=4.28.0
sentencepiece
gradio



LCFT Train

```
bash ./shell/instruct_7B.sh random_seed
```

LCFT Evluate

```
bash ./shell/evaluate.sh  output_dir
```
