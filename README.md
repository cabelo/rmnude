
![image](https://github.com/cabelo/rmnude/assets/675645/22467cdb-362b-498d-878c-464304113009)

# rmnude
Combat child pornography on the Internet. This project utilizes deep learning and computer vision to scan pages on servers and block viewing of nude, pornographic images and also to combat child pornography. The Firefox WebExtension  will send the URL of the image to the webAPI for processing, if the server finds nudes the plugin obfuscates the image preview. 

# Overview / Usage

The project utilizes deep learning and computer vision to scan pages on servers and block viewing of nude, pornographic images and also to combat child pornography.

# Methodology / Approach

The project utilizes deep learning and computer vision to scan pages on servers and block viewing of nude, pornographic images and also to combat child pornography.

Using deep learning with vision computes, based on the amount of skin tone pixel (grouped in the body) the algorithm detects the probability of nudes.

Processing takes place on Intel servers (using IPP / TBB), but the images will be sent by a Firefox extension. This extension will send the URL of the image to the webAPI for processing, if the server finds nudes the plugin obfuscates the image preview.

The project has the objective in the second version to calculate the age estimate, if the image contains children the server will send alert to the configured recipients.

# Technologies Used
- WebExtension for Firefox
- openCV
- TBB
- IPP
- OpenVino

![image](https://github.com/cabelo/rmnude/assets/675645/47cca2ee-3f26-49b1-a117-141ab926cb10)

[![image](https://github.com/cabelo/rmnude/assets/675645/4eec1838-09fb-4cba-888e-86fec40782b0)](https://vimeo.com/385597158)
