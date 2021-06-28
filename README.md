# Deepstream_with_jetson_nano[NVIDIA]

<h3>Prerequisites:</h3>
- DeepStreamSDK 5.1<br>
- Python 3.6<br>
- Gst-python<br>

<h3> Usage:</h3>
<h6>$ python3 deepstream_nvdsanalytics.py [uri1] [uri2] ... [uriN]<br>
e.g.<br>
  $ python3 deepstream_nvdsanalytics.py file:///path/to/.mp4/file file:///path/to/.mp4/file<br>
  $ python3 deepstream_nvdsanalytics.py rtsp://127.0.0.1/video1 rtsp://127.0.0.1/video2<br> </h6>
  

<h3>Outputs: </h3>
<p>
 1. With one source:<br>
 <img src="./deepstream_analytics_plugin/op_images/single_source.png", height="300", width="200"></img>&nbsp&nbsp&nbsp&nbsp
 </p><br>
 
<p>
 2. with multiple source:<br>
 <img src="./deepstream_analytics_plugin/op_images/multi_source.png", height="300", width="200"></img>&nbsp&nbsp&nbsp&nbsp
 </p><br>

