# Deep Learning Session

## Tea Mapping in Kenya with Deep Learning

This Colab-based notebook is part of a PhD workshop, [Satellite Data in Agricultural and Environmental Economics](https://www.agraroekonomik.de/M6900-Wuepper-Satellite%20Data%20in%20Agricultural%20and%20Environmental%20Economics.html). It demonstrates how to map tea plantations at the foot of Mount Kenya using satellite imagery and a U-Net model in PyTorch.

## What it covers
- Load raster and vector geospatial data with `torchgeo`
- Apply augmentations (`albumentations`)
- Train a U-Net (ResNet-18) for binary segmentation (tea / no tea)
- Evaluate with accuracy and Intersection over Union
- Save metrics and best model

## Run it
[Open in Google Colab](https://colab.research.google.com/github/Wycology/dl_tea_mapping/blob/main/dl_tea4.ipynb)

## Data
Ensure you upload the `.tif` (satellite image) and `.gpkg` (training labels) files in `/content/` before running the Google Colaboratory.

## Instructors
Developed for a PhD workshop by David Wuepper, Lisa Biber-Freudenberger, Hadi, and Wyclife Agumba Oluoch.

[Land Economics Group](https://www.ilr1.uni-bonn.de/en/research/research-groups/land-economics)

[Center for Development Research](https://www.zef.de/zefhome.html)

## License
MIT License.
