# GIANT - Genomic sequence Integrated with chromatin Accessibility or inferring Nascent Transcription

GIANT is a deep learning model for predicting cell type-specific nascent RNA transcription profiles from genomic sequence and chromatin accessibility.

This repository currently provides the core model implementation and training code used for GIANT. Additional documentation, preprocessing workflows, inference code, and pretrained model weights will be added in future updates.

## Installation

GIANT was developed and tested with:

* Python 3.9.7
* PyTorch 2.5.0
* CUDA 12.4

Clone the repository and install the required Python packages:

```bash
git clone https://github.com/linghuajiang/GIANT.git
cd GIANT

pip install -r requirements.txt
```

For GPU training, a PyTorch installation compatible with the local CUDA environment is required.

## Training

The main training implementation is provided in:

```text
src/train.py
```

Training can be launched with:

```bash
bash scripts/run_train.sh
```

Users should update the data paths and other environment-specific settings in the training script before running the model.

## Pretrained model weights

Pretrained model weights can be downloaded from https://zenodo.org/records/22659557

## Citation

Citation information will be added upon publication.

## License

This project is licensed under the MIT License.

