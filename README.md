MobileNet Game

This is a fun, and simple game that uses the MobileNet computer vision model to classify images directly from the webcam.

This was part of the "Practical Machine Learning in Javascript" book by Charlie Gerard.

Instructions:
1. The app will ask the user to find a specific object out of the 1000 classes that the model has been trained on.
2. Once the webcam has loaded, the user can take a picture, and the snap will be converted to a tensor, a data structure that the model can work with.
3. The app will then display the three most probable predictions model predictions.
4. If the model has detected the asked object, the corresponding prediction will be green-colored, otherwise, it will be red.
5. At any point, the user can ask for another object using the 'Next Item' button.
