# Tomograph
Hi! We created a project which explains how to convert image into a sinogram and vice versa with filtering, normalization and visualization. You can see the progress by moving the progress bar and saving to a DICOM file! [Here](https://github.com/HelenaMaslowska/Tomograph/blob/main/tk.ipynb) is a main code, enjoy!

## Used libraries
* numpy - filtering with convolve arrays and math
* scikit-image - draw lines using ski.draw.line_nd(E, D), image
* matplotlib - plots
* pydicom - extension of a file
* cv2 - filtering with cv2.filter2D
* ipywidgets - interact (slider)

## Slider
One of the most interesting part of an experiment. Move progress bar to check how is Radon transform actually works! I wish I don't spoiler too much...

![image](https://user-images.githubusercontent.com/44245185/226763895-f8976e3e-b6df-4909-b566-7bd1bd717af2.png)


## Summary
All the result of an experiment is summarized [here](https://github.com/HelenaMaslowska/Tomograph/blob/main/tk.ipynb) by MSE measure at the bottom of the page.

# Source image
![image](https://user-images.githubusercontent.com/44245185/226759448-4786b3ac-628b-4f64-8e74-3ee2b950f6ad.png)

# Sinogram created by Radon transform
![image](https://user-images.githubusercontent.com/44245185/226759472-b737ae44-05ec-461d-b01b-1260277ec225.png)

# Sinogram from OpenCV library (cv2.filter2D)
![image](https://user-images.githubusercontent.com/44245185/226759608-fe6a36e8-814c-466b-be63-eb3e1015578a.png)

# Sinogram with numpy library (np.convolve)
![image](https://user-images.githubusercontent.com/44245185/226759822-709ed3de-7a8e-4d7c-b594-48049bde4339.png)

# Invert Radon transform
![image](https://user-images.githubusercontent.com/44245185/226759563-e9eb9787-1b00-4267-998e-9979d8dce82c.png)

# Invert Radon transform with openCV
![image](https://user-images.githubusercontent.com/44245185/226759887-cc98e3d9-c145-4667-b033-3da50d54be28.png)

# Invert Radon transform with numpy
![image](https://user-images.githubusercontent.com/44245185/226759960-7621a75d-bddd-4778-aa8b-1e278af22751.png)


## Authors
- Marcin Szwarc
- Helena Masłowska
