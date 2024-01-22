# ConvNeXtV2-Unet
pytorch, ConvNeXtV2,Unet


Adapted from https://github.com/facebookresearch/ConvNeXt-V2

# Usage
```
from Unet import ConvNeXtV2
model = ConvNeXtV2()

x = torch.randn(1, 3, 256, 256)
y = model(x)
```
