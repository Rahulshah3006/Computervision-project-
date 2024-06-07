# Computervision-project-

* Pre-process video and extracting frames :
  - Here by, I have preprocess video by computing their similarity using Intersection over union (IOU) between processed frames of videos and sample images and based on that we have extracted frames with similarity of thresold greater than a threshold ( in our case we have set 0.95) and finally used image with similarity with greater than 0.95 ( i.e. 0.99 in our case most perfect one ).
 
---
**NOTE**
I have used trimmed video for ease of pre-processing but also in case of original video we can see around 367877 frames overall.
---

* recontruction of camera:
  - During this procedure we have find the corner coordinates  the playing area or green area using Hough transform as well as sobel gradiants.
  - yet , ball marker points to be done properly

* Reconstruct Ball Positions:
  - ......
