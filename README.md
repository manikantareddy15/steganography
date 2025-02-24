# LSB Image Steganography  
A simple Python program to hide and retrieve messages in images using **Least Significant Bit (LSB) Steganography**.  
## Features  
 Hide secret messages inside images  
 Secure with password protection (hashed using SHA-256)  
 Retrieve messages only with the correct password  
 Works with `.jpg` and `.png` images  
## Requirements  
- Python 3  
- OpenCV (`pip install opencv-python`)  
## Usage 
### **Encoding (Hiding Message)**  
1. Place your image (e.g., `mypic.jpg`) in the same directory.  
2. Run the script:  
   ```sh
   python steganography.py
 
