# Preparation
## 1. Clone this repository
```bash
git clone https://github.com/mlrepa/catalyst-2-config-api
cd catalyst-2-config-api
```

## 2. Create and activate virtual enviromnent
Install virtualenv in advance: ```pip install virtualenv```

```bash
virtualenv venv
source venv/bin/activate
```

install requirements
```bash
pip install -r requirements.txt
```

# Training
## Local run
```bash
CUDA_VISIBLE_DEVICE="0" catalyst-dl run --config=config.yml --verbose
```

## Training visualization
For tensorboard visualization use 

```bash
tensorboard --logdir=./logs/
```
