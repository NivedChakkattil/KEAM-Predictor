# KEAM Predictor API
The KEAM Predictor API is a Flask-based web application that predicts the best college and branch options for a user based on their KEAM examination rank. The application uses an algorithm developed in Python to find the best possible colleges and branches for a particular rank.

# Usage
To use the KEAM Predictor API, send a GET request to the following endpoint:


https://nivedchakkattil.pythonanywhere.com/predict/<rank>/<options>/

The API will return a JSON response containing the predicted colleges and branches along with some additional information.

# Algorithm
The algorithm used by the KEAM Predictor API is based on a custom scoring system that takes into account factors such as college reputation, course availability, and previous year cutoffs. The algorithm was developed using the pandas library in Python.

# Future Plans
In the future, we plan to enhance the KEAM Predictor API by adding more data sources and improving the accuracy of the predictions. We also plan to develop a web interface for the API to make it easier for users to interact with.

# License
The KEAM Predictor API is released under the MIT License. See LICENSE for more information.
