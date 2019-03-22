Proposed Features
------
- Stop and go before stop sign.
- Stop and go before traffic lights.
- Vision based traffic sign/traffic light/white lines detection
- Vision/Geolocation based traffic sign/traffic light/white lines localization
- Neural network models trained using comma2k19 drive data, better transfer learning from driving model.

Sample data and Groundtruth extraction
------
- Stop sign 25 meters away, zerba and text in the middle, no white lines.
![](https://i.ibb.co/jLBLLF1/Screenshot-from-2019-03-22-08-05-46.png)
- Zebra only, no stop sign.
![](https://i.ibb.co/yh8VYz6/Screenshot-from-2019-03-22-08-06-25.png")
- Other white things on the road, a bicycle shape. Should be ignored by the model.
![](https://i.ibb.co/nQhs6C6/Screenshot-from-2019-03-22-08-10-18.png")
- White lines while passing traffic lights
![](https://i.ibb.co/Bj7yNn6/Screenshot-from-2019-03-22-08-11-08.png")
- White lines blocked by cars
![](https://i.ibb.co/cJpypPW/Screenshot-from-2019-03-22-08-13-47.png")
- White lines with angles
![](https://i.ibb.co/THcz2F9/Screenshot-from-2019-03-22-08-14-58.png")
- White lines and traffic lights at night
![](https://i.ibb.co/d0dZLNW/Screenshot-from-2019-03-22-08-19-59.png")
- Traffic lights messed up with car tail lights
![](https://i.ibb.co/pxgKk6j/Screenshot-from-2019-03-22-08-21-13.png")
- Green traffic lights 50 meters away
![](https://i.ibb.co/PCmHqLL/Screenshot-from-2019-03-22-08-21-39.png")
-  Red traffic lights 50 meters away
![](https://i.ibb.co/6g2Lf8c/Screenshot-from-2019-03-22-08-23-40.png")
