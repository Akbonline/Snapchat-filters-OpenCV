# Snapchat Filters using OpenCV



## Description

This repository contains python implmentation of various snapchat like face filters and masks. 

## Getting Started

### Dependencies

* Python
* The program makes use of Dlib-facial feature points
* OpenCV
* Tkinter
* Shape predictor 68 face landmark points Model


### Installing
* Git clone repository: 
```
git clone https://github.com/Akbonline/Snapchat-filters-OpenCV.git
```
* Make sure to install the dependencies:
```
pip install dlib
```
* Any modifications needed to be made to files/folders
```
pip install opencv-python
```

### Executing program
* Before running the program, please navigate to the resources folder and merge/extract the following files:
   * shape_predictor_68_face_landmarks.7z.001
   * shape_predictor_68_face_landmarks.7z.002
   * shape_predictor_68_face_landmarks.7z.003

* To run different filters and masks, run using: 
   * For surgical mask filter
```
python mask_dlib.py
```
   * For annabelle face mask
```
python annabelle.py
```
   * For Batman mask filter
```
python batman Mask.py
```
   * For Cat mask filter
```
python cat.py
```
   * For Clown Nose filter
```
python clown.py
```
   * For Moustache face filter
```
python moustache.py
```
   * For Pig Nose face filter
```
python pig.py
```

## Help

If you see any errors, please make sure you've installed Dlib, opencv-python modules. Also make sure to merge the three shape_predictor_68_face_landmarks dataset files from resources folder. 
If you still encounter any issues or errors, feel free to reach out!

## Authors

Akshat Bajpai
* Email: akshatbajpai.biz@gmail.com



## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [Sergio's Youtube tutorial on simple dlib](https://www.youtube.com/watch?v=IJpTe-1cimE&t=1425s)
