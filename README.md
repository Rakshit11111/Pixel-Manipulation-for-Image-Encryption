# Pixel-Manipulation-for-Image-Encryption

Image Encryption and Decryption using Pixel Manipulation

This Python project demonstrates a basic method of encrypting and decrypting images by manipulating the pixel values. Specifically, it swaps the red and blue channels of each pixel to create an encrypted image. The process is reversible, allowing the original image to be restored.


Features

	•	Encrypt Image: Encrypt an image by swapping the red and blue channels of each pixel.
	•	Decrypt Image: Restore the original image by reversing the swapping process.
	•	Supports Any Image: Works with any image format supported by the PIL (Pillow) library.

How It Works

	1.	Encryption:
	•	For each pixel (R, G, B) in the image, the red and blue channels are swapped, resulting in a new pixel (B, G, R).
	2.	Decryption:
	•	The process is reversed by swapping the red and blue channels again, restoring the original pixel values.

Code Explanation

Functions

	1.	encrypt_image(input_path, output_path, key)
	•	Takes the input image and swaps the red and blue channels of each pixel.
	•	Saves the encrypted image to the specified output path.
	2.	decrypt_image(input_path, output_path, key)
	•	Reverses the pixel manipulation process to restore the original image.
	•	Saves the decrypted image to the specified output path.


