# PencilSketch

Convert your images into captivating pencil sketches using Python.

## Files

1. **PencilSketch.py**: Python code to convert an image to a pencil sketch.
2. **golden_trio.jpg**: Sample input image to be transformed.
3. **output.png**: A visual representation showcasing both the input image and the resulting pencil sketch.
4. **StagesOfConversion.png**: Illustrates the sequential transformation process, including grayscale conversion, image inversion, smoothing, and the final sketch achieved through a blend function (dodgev2).

## How It Works

The process involves the following steps:
1. Convert the image to grayscale.
2. Invert the grayscale image.
3. Apply smoothing techniques.
4. Employ a blend function (dodgev2) to achieve the pencil sketch effect.

## Usage

Ensure you have the **opencv-python** package installed:
```bash
pip install opencv-python
