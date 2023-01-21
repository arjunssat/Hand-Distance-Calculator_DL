# Vehicle Detection and count_DL
<ul>The model detects the count of vehicle passing through the road and it analyses the traffic in that area based on it.</ul>

<ul>
  <li>The code here depicts the use of libraries such as OpenCv,Numpy.Here the vehicles are detected by the use of corrseponding HaarCascade file.
  Each haarcascade file is used for bike,car,truck detections.</li>
  <li>The cascade classifier is then used to detect muliscale values and the ROI is determined and the rest area is blured.The code then depict the input of a line at a certain height,width of the frame where the detected classifer ROI frame passes through the line a count is noted and the function is inputed in a while loop where each ROI frame is counted till the video time elapses and th total count is measured.</li>
  
</ul>

<ul><b>Scope</b></ul>

<ul>
<li>The detection counter could be used in areas where the traffic type could be observed,The type of vehicle that passes through at a time could be know and the peak hours traffic could be determined and the corrseponding evalution could be done and monitored to reduce the congestion in areas and divert heavy vehicles as per the peak hours as to avoid huge congestions and delays.</li></ul>
