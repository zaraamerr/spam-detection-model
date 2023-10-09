# spam-detection-model
# overview:
this is a spam-detection application built using python, scikit-learn, and flask. it allows users to classify SMS messages as spam vs. real messages based on a trained machine learning model! 
# how it works:
the machine learning model is trained on a csv file that contains around 5,700 SMS messages which are labeled either spam or ham.
example: "Click on this link below for a FREE shopping trip with no catch! : spam
         "I'll call you later, Becca."                                     : ham. 
the powerful scikit-learn library uses its algorithms for classification, regression, and anomaly detection. plain text, such as SMS messages, are turned into feature vectors that machine learning models can understand using vectorizers.
once the model is trained and tested, i created a flask app that lets users query their own SMS message examples in the URL and the application will classify the message as spam or ham, as well as, providing the model's confidence in its prediction.
# the future of this application:
right now, the flask app is minimal. its UI is not yet designed for optimal user friendliness or accessibility. i am working on improving the UI so that it is easy for users to navigate!
# how to run this application:
clone the repo to your local machine
ensure you have all dependencies installed in your machine such as flask, pandas, scikit-learn, numpy, and beautifulsoup4
run python app.py
open the application in your web browser through the local host link
query an SMS message in the URL to see the model's prediction on whether the message is spam or ham and the probability measures!
