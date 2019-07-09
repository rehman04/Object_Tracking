# Object_Tracking
---
### This repository is defining different types of Object Tracking techniques using Python and OpenCV.
### Nevertheless the types are Below:
- ## Optical Flow:
     - Optical FLow tracking is use where we want to track motion of moving objects and to predict there motion in the next frame.
     [Optical Flow Blog](https://blog.nanonets.com/optical-flow/)
- ## MeanShift and CamShhift:
     - The technique Meanshift takes the means of the present frame to reach to the center of targeted frame, Camshift do the same but it also readjust its window size when the target is moving far or coming close by fitting ellipse calculation.
     [OpenCv_Docs](https://docs.opencv.org/master/df/def/tutorial_js_meanshift.html)
- ## Tracking API's:
     - There is 5 different API's in this repo in the file Tracking_Api's. All give different performances in different scenarios.
         1. Boosting
         2. MIL Multiple instance Learning
         3. KCF kernelized correlation filters
         4. TLD Tracking,Learning,Detection
         5. Median Flow 
     - There is video also attached of tracking API Boosting with the filename (Tracking_API_TrackerBoosting.mp4).
     - With All These techniques we first define Region Of Interest Manually then the Alogrithm Starts.
