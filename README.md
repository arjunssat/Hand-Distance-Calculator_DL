# Vehicle Detection and count_DL


<ul>The model counts the number of vehicles passing through a road and analyzes the traffic in that area based on the count. The code employs libraries such as OpenCV and Numpy to detect vehicles using corresponding HaarCascade files. The HaarCascade files are used for detecting bikes, cars, and trucks. The cascade classifier is then used to detect multiple scales and determine the region of interest (ROI), while the rest of the area is blurred. The code inputs a line at a specific height and width of the frame, and as the detected ROI frame passes through the line, a count is recorded. This process is repeated in a while loop until the video time elapses, and the final count is calculated.

<ul><b>Scope</b></ul>
The vehicle detection counter could be used in areas to observe the type of traffic, identify the type of vehicles passing through at a specific time, and determine peak hours traffic. The information obtained from this evaluation could be used to reduce congestion in areas by diverting heavy vehicles during peak hours to avoid delays.</ul>
