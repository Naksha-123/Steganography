SECURE DATA HIDING IN IMAGES USING STEGANOGRAPHY
Introduction
This project implements Steganography, a technique for hiding secret messages inside digital media, such as images or audio files. The project allows users to embed a hidden message within an image and later extract it without noticeable alterations to the image quality.

Features
Encode Message: Hide text messages inside an image.
Decode Message: Extract hidden messages from a stego-image.
Supported Formats: Works with jpg image formats.
User-friendly Interface: Simple command-line or GUI-based interaction.

Technologies Used:
Programming Language:Python 
Libararies: OpenCV,NumPy,Tkinter

Applications:  
Secure Communication – Hide confidential messages in images.  
Digital Watermarking – Embed hidden text into images for authenticity.  
Data Protection – Store sensitive information in images securely.  

Example Usage  
Encrypt an Image:  
   - Choose an image file.  
   - Enter a secret message and a password.  
   - Click "Encrypt Image" to hide the message.  

Decrypt an Image:  
   - Select the modified image.  
   - Enter the correct password.  
   - Click "Decrypt Image" to reveal the message.

Future Enhancements 
Add support for larger messages using advanced encoding techniques.  
Implement a *Drag-and-Drop* feature for file selection.  
Improve security using encryption before embedding the message.  
Develop a mobile or web-based version for accessibility.  

Conclusion  
This Image Steganography tool provides a simple yet powerful way to hide and retrieve messages inside images securely. With a friendly GUI and strong encryption logic, it ensures secure data hiding without affecting image quality.
