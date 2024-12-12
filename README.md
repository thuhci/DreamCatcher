# DreamCatcher
This repo includes the official baseline implementations of "DreamCatcher: A Wearer-aware Sleep Event Dataset Based on Earables in Non-restrictive Environments"

We release the audio classification set for DreamCatcher using [Huggingface Datasets](https://huggingface.co/datasets/THU-PI-Sensing/DreamCatcher). You can load the dataset with one line of code:
```python
from datasets import load_dataset
dataset = load_dataset("THU-PI-Sensing/DreamCatcher")
```

For full dataset with imu to perform sleep event detection, please contact the authors.