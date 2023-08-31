# Writeup: Track 3D-Objects Over Time

Please use this starter template to answer the following questions:

### 1. Write a short recap of the four tracking steps and what you implemented there (filter, track management, association, camera fusion). Which results did you achieve? Which part of the project was most difficult for you to complete, and why?

## EX_S1

the following steps were necessary to complete the task: 
- filter pointclouds and set all negative values to zero 
- normalize range channel and convert to 8bit 
- filter out outliers in intensity channel with 1 percentile and 99 percentile and convert to 8bit 
- stack vertically range and intensity 
- crop range image -90 to +90 degrees in direction of x-axis
<img src="img/range_image_screenshot_29.08.2023.png"/>



### 2. Do you see any benefits in camera-lidar fusion compared to lidar-only tracking (in theory and in your concrete results)? 


### 3. Which challenges will a sensor fusion system face in real-life scenarios? Did you see any of these challenges in the project?


### 4. Can you think of ways to improve your tracking results in the future?

- One way to improve the tracking results is to fine-tune detection models on specific needs 
- Other way is to use other fusion strategies e.g. early fusion, middle fusion, late fusion 

