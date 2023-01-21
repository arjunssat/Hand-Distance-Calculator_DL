# Vehicle Detection and count_DL
<ul>The model detects the count of vehicle passing through the road and it analyses the traffic in that area based on it.</ul>

<ul>
  <li>The code here depicts the use of libraries such as OpenCv,Numpy.Here the vehicles are detected by the use of corrseponding HaarCascade file.
  Each haarcascade file is used for bike,car,truck detections.</li>
  <li>The cascade classifier is then used to detect muliscale values and the ROI is determined and the rest area is blured.The code then depict the input of a line at a certain height,width of the frame where the detected classifer ROI frame passes through the line a count is noted and the function is inputed in a while loop where each ROI frame is counted till the video time elapses and th total count is measured.</li>
  
</ul>
