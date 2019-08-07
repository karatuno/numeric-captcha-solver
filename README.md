# numeric-captcha-solver
### Predicting numeric digits in image
#### input image
![image](https://raw.githubusercontent.com/karatuno/numeric-captcha-solver//master/unsolved-captchas/electoral-captchas/11147.png)
#### result:
11147

### Data
solved-captchas(940 files) - folder containg solved image captchas with name of file as numerics in image
unsolved-captchas(1500 files) - folder containg unsolved image captchas

### Steps:

##### 1. Extracting the digits from the image:
######  1.1. Preprocessing the image and converting to grayscale
######  1.2. Extracting and sorting the contours from left to right
######  1.3. Looping on all the images in folder to extract number image which are sorted from left to right.
######  1.4. Flattening the extracted digit image to 1D matrix with pixel intensities
######  1.5. Assigning the image and row in the dataframe to thier corresponding digit string using filename.
##### 2. Machine Learning Modeling
##### 3. Predictions¶

#### Note: Renamed files in unsolved-captchas to expected answers.
##### To run the program delete unsolved-captchas folder and rename unsolved-captchas-original to unsolved-captchas
