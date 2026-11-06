# 📦 Computer Vision with PyTorch Masterclass — Public Asset CDN

This repository serves as the public static asset distribution host for the **Computer Vision with PyTorch Masterclass** workbook series.

## 📁 Repository Contents

- `assets.zip` (25 MB): Full portable archive containing all 56 high-resolution architecture diagrams, photographic test benchmarks, and capstone assets.
- `assets/`: Directory containing all individual uncompressed image assets and publication figures.

## ⚡ Direct Download for Google Colab

To programmatically fetch and unpack workbook assets inside Google Colab:

```bash
wget -q https://raw.githubusercontent.com/standungan/cv-pytorch-workbook-asset/main/assets.zip -O assets.zip
unzip -q assets.zip -d ./assets
```

Or via Python:
```python
import urllib.request
urllib.request.urlretrieve(
    "https://raw.githubusercontent.com/standungan/cv-pytorch-workbook-asset/main/assets.zip",
    "assets.zip"
)
```