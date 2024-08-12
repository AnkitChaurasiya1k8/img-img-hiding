# Image Steganography Project

This project demonstrates a method of image steganography, where one image is hidden inside another image. The project includes encoding, decoding, and quality assessment using PSNR (Peak Signal-to-Noise Ratio).

## Features

- **Encoding:** Hide one image within another by embedding the binary data of the hidden image into the least significant bits of the carrier image.
- **Decoding:** Extract the hidden image from the encoded carrier image.
- **Quality Assessment:** Calculate the PSNR value to assess the quality and similarity between the original and encoded images.

## Tools and Libraries Used

- **Python:** Core programming language.
- **PIL (Pillow):** Used for image processing.
- **NumPy:** Utilized for numerical operations in PSNR calculation.
- **OpenCV:** Used for image comparison in PSNR calculation.

## How to Use

### Encoding an Image

To hide an image inside another, use the following command:

```bash
python encode.py path/to/carrier_image.jpg path/to/secret_image.jpg path/to/output_image.png
```
### Decoding the Image
To extract the hidden image from the encoded image, use:

```bash
python decode.py path/to/encoded_image.png path/to/output_image.pn
```
### Calculating PSNR
To calculate the PSNR value between the original and encoded images
```bash
python psnr.py
```
### Requirements
Make sure you have the following Python libraries installed:
```bash
pip install Pillow numpy opencv-python
```
