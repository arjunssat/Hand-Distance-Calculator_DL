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

<ul>The model counts the number of vehicles passing through a road and analyzes the traffic in that area based on the count. The code employs libraries such as OpenCV and Numpy to detect vehicles using corresponding HaarCascade files. The HaarCascade files are used for detecting bikes, cars, and trucks. The cascade classifier is then used to detect multiple scales and determine the region of interest (ROI), while the rest of the area is blurred. The code inputs a line at a specific height and width of the frame, and as the detected ROI frame passes through the line, a count is recorded. This process is repeated in a while loop until the video time elapses, and the final count is calculated.

<ul><b>Scope</b></ul>
  : The vehicle detection counter could be used in areas to observe the type of traffic, identify the type of vehicles passing through at a specific time, and determine peak hours traffic. The information obtained from this evaluation could be used to reduce congestion in areas by diverting heavy vehicles during peak hours to avoid delays.</ul>
