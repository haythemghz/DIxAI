# Pre-trained Checkpoints

This directory stores the pre-trained weights for the Amortized Explainer.

## Models
- `resnet50_amortized_explainer.pth`: Trained on ImageNet-1K (Validation Split).
- `densenet121_amortized_explainer.pth`: Trained on CheXpert.

## Reproducibility
To retrain these models from scratch, use the provided training script:

```bash
# Train ImageNet Explainer
python experiments/main_train_amortized.py --backbone resnet50 --data-path /path/to/imagenet --epochs 10
```

## Download
If you do not wish to retrain, download the weights from the official project repository releases page:
[Link to GitHub Releases]
