# Art Style Transfer

Deep Learning Style Transfer Notebook
This project is centered around the fascinating world of neural style transfer, an innovative technique that leverages deep neural networks to blend the artistic style of one image with the content of another. By exploring this notebook, you'll dive into the process of transforming images using the power of deep learning, creating stunning, art-inspired visuals from ordinary photos.

## Implementation Details

- **Generative Model**: Implements a generative model architecture capable of transferring artistic styles.
- **Feature Extraction**: Utilizes VGG16 architecture to extract features from input images.
- **Style Loss Calculation**: Calculates style loss using feature maps extracted from VGG16.
- **Content Loss Calculation**: Incorporates content loss to ensure preservation of original image structure.

### tinytorchutil Package

This project makes use of `tinytorchutil` ([Git-Repo](https://github.com/Chainathan/tiny-torch-util)), a personal toy package containing a collection of utility functions found useful. Install it using pip:

```bash
pip install tinytorchutil
```
