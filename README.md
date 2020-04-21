# Generate-and-scan-QrCode-using-zxing-library

Here zxing library is used for scanning and generating QR code

## Dependency

in `build-gradle` app we add

<img src="qrcode/qr1.JPG">

and `manifests` we need to add `Camera` permission for scanning the QR code

<img src="qrcode/qr2.JPG">

and for material design of `edittext` we add material design dependency

<img src="qrcode/qr7.JPG">

## Getting Started

Here we add two buttons, one for generating QR code using our own number and one is for scanning QR code

<img src="qrcode/qr6.JPG" width=400 height=400>

### Generate your QR

when we click generate button a new layout appeared where we need to add your phone number to create your own QR code

<img src="qrcode/qr8.JPG">

after adding phone number and clicking generate button we can genrate our QR code

<img src="qrcode/qr5.JPG">

### Scan QR code

when we click scanning button our camera intent will activat and camera opened with a text `scanning`

<img src="qrcode/qr3.JPG">

after scannig the QR code the result of the QR code will appeared in a Box with the result and `Copy` and `Cancel` buttons

<img src="qrcode/qr4.JPG">

# ScreenShots

<img src="qrcode/1.jpg" width=200 height=400> <img src="qrcode/2.jpg" width=200 height=400> <img src="qrcode/3.jpg" width=200 height=400> <img src="qrcode/4.jpg" width=200 height=400>  <img src="qrcode/5.jpg" width=200 height=400> 


