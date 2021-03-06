#CVriousity - An OpenCV experiment for Android devices
======================================================

Introduction
------------
CVriousity is an OpenCV experiment developed by Ramiro Oliva for Android platform as part of his MSc on Free Software's final research project about Computer Vision (paper url...).

The purpose of this app is to evaluate OpenCV's ability to detect art imagery using best methods available for current version on Android port. The methods used are aligned to the research in which, from +30 combinations of detectors, descriptors and matchers, a few ones were singled out as best choices. This app allows you to choose from these selected combinations of methods (like FAST and ORB) so you can check their performance and efficacy from your own device and in realtime.
The app is 100% free source software. See LICENSE for licensing details.
The official repository of this software is:
https://github.com/RamiroOliva/CVriousity.git

Please, feel free to contact me (ramiro_oliva@hotmail.com or @RamiroOliva) if you have any questions.

Build prerequisites
-------------------
You must have a proper OpenCV setup environment (see http://opencv.org/) including Eclipse, OpenCV and Android NDK.

Installation
------------
The app is available on Google Play (url ...). It has been only tested on a LG E370 (Optimus SOL) Android device. If you find any problem, please contact me.

Usage
-----
The app allows you to detect objects or images in the scene viewed through device's camera in realtime. You can choose one of the following methods (tap on the menu button on Android device to change active method):
- FAST/BRIEF - fastest method / less accuracy. Won't work with rotated images, so you must have the image in portrait mode. 
- FAST/FREAK - a variation of the previous one, rotation invariant.
- ORB - good tradeoff between speed and accuracy.
- MSER/FREAK - good accuracy but slower.
- GFTT/FREAK- best accuracy but the slowest method of the five.

Tap on the screen to focus camera.
You can also double tap the screen to freeze the image and let the app try to detect images using each of the available methods.

The app comes with 10 art sample images which are automatically added to the catalog (database) the first time the app is run.
A reference sheet for the images can be downloaded from https://www.dropbox.com/sh/0pqe5vzr557hrsu/pmpmA1Wkee
Individual images can be viewed online at Web Gallery of Art (http://www.wga.hu)

Art:
Image 1 - "Allegory", AACHEN, Hans von
http://www.wga.hu/art/a/aachen/allegory.jpg

Image 2 - "Bacchus, Ceres and Cupid", AACHEN, Hans von,
http://www.wga.hu/art/a/aachen/bacchus.jpg

Image 3 - "Joking Couple", AACHEN, Hans von,
http://www.wga.hu/art/a/aachen/j_couple.jpg

Image 4 - "The Archangel Michael", ABADIA, Juan de la,
http://www.wga.hu/art/a/abadia/michael.jpg

Image 5 - "Albarello", ABAQUESNE, Masséot,
http://www.wga.hu/art/a/abaquesn/albarell.jpg

Image 6 - "Ceramic Floor", ABAQUESNE, Masséot,
http://www.wga.hu/art/a/abaquesn/floor1.jpg

Image 7 - "Ceramic Floor", ABAQUESNE, Masséot,
http://www.wga.hu/art/a/abaquesn/floor2.jpg

Image 8 - "The Flood", ABAQUESNE, Masséot,
http://www.wga.hu/art/a/abaquesn/theflood.jpg

Image 9 - "Chimney breast", ABBATE, Niccolò dell',
http://www.wga.hu/art/a/abbate/chimney1.jpg

Image 10 - "Chimney breast", ABBATE, Niccolò dell' (2)
http://www.wga.hu/art/a/abbate/chimney2.jpg

You may also take your own pictures of small objets using device's builtin camera. I recommend you to put a blank, white sheet, below the object before taking the photo. The app will automatically crop and resize image before adding it to the catalog.

