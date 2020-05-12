# People-Counter-Application
In this project, i utilize the Intel® Distribution of the OpenVINO™ Toolkit to build a People Counter app, including performing inference on an input video, extracting and analyzing the output data, then sending that data to a server. These model was deployed on the edge, such that only data on 
1) the number of people in the frame,
2) time those people spent in frame, and 
3) the total number of people counted are sent to a MQTT server; inference will be done on the local machine.
