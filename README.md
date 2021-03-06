# FeelTube
A simple app that classifies a user's emotion based on facial landmarks!

### Running the project

* The project as of now has 3 running functionalities

* To run the Emotion Classifier on Jeffa dataset:

```sh
cd /path/to/your/directory
python emotrainer.py
```

* After which the program will show you a set of 5 images that are chosen at random as test images:
![alt text](https://github.com/ManishShettyM/FeelTube/blob/master/images/ip.png)

* Closing that shows us the histogram plotted using LPB:
![alt text](https://github.com/ManishShettyM/FeelTube/blob/master/images/hist.png)

* Closing that gives us the output with red text representing wrong prediction and green being right:
![alt text](https://github.com/ManishShettyM/FeelTube/blob/master/images/op1.png)

* The terminal has information about the mean accuracy:
![alt text](https://github.com/ManishShettyM/FeelTube/blob/master/images/terminal.png)

* Sometimes output will have errors :
![alt text](https://github.com/ManishShettyM/FeelTube/blob/master/images/test2.png)

* To run the webscraping application for emotion to genre selection:

```sh
cd /path/to/your/directory
python emovie.py
```

* To run the face and features detector:
This uses the 68 landmarks method:
![alt text](https://raw.githubusercontent.com/username/projectname/branch/path/to/img.png)

```sh
cd /path/to/your/directory
python facial_landmarks.py --shape-predictor shape_predictor_68_face_landmarks.dat --image images/<imagename>.jpg
```

