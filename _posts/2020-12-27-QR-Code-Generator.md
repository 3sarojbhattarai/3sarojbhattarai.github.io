---
layout: post
title: Generate QR code using Python
---

A QR code ( Quick Response code) is a two dimensional bar code which is used for its
fast readability and comparatively large storage capacity. It consists of black squares arragned in a square grid on a white background.

Python has a library called qrcode for generating QR code iamges. 

`pip install qrcode` 



# Code


```
# Importing library
import qrcode
 
# Data to be encoded
data = 'QR Code using make() function'
 
# Encoding data using make() function
img = qrcode.make(data)
 
# Saving as an image file
img.save('MyQRCode1.png')
```

