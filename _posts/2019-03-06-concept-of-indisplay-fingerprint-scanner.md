---
layout: post
title:  "Concept of In-Display Fingerprint Scanner"
author: kaustubh
categories: [ explanation, guide]
image: assets/thumbnails/indisplay.jpg
comments: true
---

With the release of Vivo Nex in December 2018 and Samsung S10 and Samsung S10+ in February 2019, there is a strong buzz around and many of you might be thinking about how exactly the in-display fingerprint technology works. Other phones like OnePlus 6T and Nokia 9 Pureview also support in-display fingerprint scanners. So, in this article, I would like to discuss the working of this amazing technology. This is a bit technical concept but I will try to explain you in as simple language I can.

## History

Back in 2013, Qualcomm acquired a small company called Ultra-Scan which produced ultrasound readers for the US government. In 2015, the annual tech summit was around the corner and Qualcomm unveiled its Snapdragon Sense ID which was the first prototype of the in-display fingerprint scanner. Recently in 2019, the company has confirmed that it is working on a newer version namely a 3D sonic scanner.

## Optical Scanning (Old technology)

The initial phase of biometrics uses optical scanning technology in which a camera would capture a model picture of the finger and compare it with the sample taken while capturing the test images. This technology can only be used in AMOLED (Active Matrix Organic Light Emitting Diode) displays as there is no backlight in it and every pixel is itself working [Comment down below if you want a separate article about types of displays]. The camera illuminates light onto the finger and records the image. There are many drawbacks with this:
- The portion of fingerprints should be clean as a dirty scanner would give faulty results.
- It is less secure as compared to ultrasonic technology as a perfect fingerprint image can be reproduced and the scanner can be easily fooled.
- The finger also should be clean and non-contaminated.

## Ultrasonic (New and recently used)

Qualcomm uses this technology for the production of its latest in-display fingerprint scanner. To capture the fingerprint, the hardware uses both transmitter and a receiver. An ultrasonic pulse is transmitted onto the finger placed on the scanner. Some of it is absorbed and some of it is transmitted back to the receiver depending upon the features of each finger. But here is the catch, there is no microphone for listening to returning signals, instead, there is a sensor that calculates the mechanical stress that is used to detect the intensity of the returning ultrasonic impulse at different points of the scanner. When it captures enough data, it uses it for depth analysis and reproduces a 3D model of the scanned fingerprint. These 3D details are much difficult to forge than 2D versions of the technology making it very much secure.

The scanner can penetrate through enough depth. So, it can be embedded in under-display for a more discrete look at the device. The main advantage of using this technology is:
- It is very much secure than that optical technology as it reproduces a 3D model of the fingerprint which can be stored using Qualcomm MSM Secure Architecture.
- How much the finger is contaminated, the scanner would perfectly as there is no image capturing by any camera.

This was all about in-display fingerprint scanners. If are liking my way of writing and want future articles just subscribe to my blog (it's free!) and leave a comment if are still confused about anything and suggest me more topics on which I can write.

Happy Reading Folks!