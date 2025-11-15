# ResNet-18 Image Classification

Small PyTorch script that uses a **pre-trained ResNet-18** model to classify images into **ImageNet-1K classes**.

## What it does

- Loads a local image (e.g. `cat.jpg`).
- Applies standard ImageNet preprocessing.
- Runs it through `torchvision.models.resnet18` with pretrained weights.
- Prints the **top-k predicted classes** and probabilities.

## Files

```text
.
├─ resnet_infer.py        # main script
├─ cat.jpg                # example image (not included here)
└─ imagenet_labels.json   # optional labels file (if not using weights.meta)
