## Image Encryption using Pixel Manipulation

This Python project encrypts and decrypts images by manipulating pixel values. The encryption is done using the XOR operation with a secret key. The same key is used to decrypt the image back to its original form.

## How it Works
- **Encrypt**: The pixel values of the image are XORed with a key to produce an encrypted image.
- **Decrypt**: The encrypted image is XORed again with the same key to retrieve the original image.

## Requirements
- Python 3.x
- Pillow library (`pip install pillow`)
- NumPy library (`pip install numpy`)

## How to Use
1. Place your image in the same folder as the script.
2. Update the `image_path` in the script with the name of your image file.
3. Run the script to generate the encrypted image and then decrypt it.
