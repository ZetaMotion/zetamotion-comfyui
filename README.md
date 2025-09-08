# Zetamotion-ComfyUI

This is a lightweight wrapper around [ComfyUI](https://github.com/comfyanonymous/ComfyUI), making its functionality available as a standard Python package installable via `pip`.

To install directly from the repository, run:

## Installation

```commandline
pip install git+https://github.com/ZetaMotion/zetamotion-comfyui.git@main
```

If the repository is private, you’ll need the appropriate authentication (SSH key or GitHub token).

## Example Usage

```Python
import zetamotion_comfyui as zmcf

print(zmcf.GaussianBlurMask.INPUT_TYPES())
```