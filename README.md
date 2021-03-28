# Labview-webservice-Website
For example sending and receiving images from internet website to Labview server ( NAT port)
# Test
## Run start webservice from project .
* Access link http://127.0.0.1:8001/processing_images/
* Go to Test upload upload file and you will see global variant changed.
# Run Product
* You need open NAT port WAN IP your computer (google.com) .
* Change IP address at index.html and your Labview application .
```
<base href="http://127.0.0.1:8001/processing_images/">
To
<base href="http://200.182.217.216:8001/processing_images/">
```
* Start Labview webservice : processing_images webservice in my application .
* Run http://200.182.217.216:8001/processing_images/
* * 200.182.217.216:8001 is your IP address NAT and 8001 is port .
# Open NAT (port)
You need Open NAT (port) your computer run Labview Webservice
# Change IP address
You need change IP address at Index.html file and Labview web service suitable with your application

