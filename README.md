# data_science_spam_prediction

The experiment is forked from https://github.com/piskvorky/data_science_python

I added a docker setup using tensorflow docker image, which make the implementation quicker and easier.

How to play with this repo
- Be sure you have docker-compose ready in your machine
- Clone this repo
- Run `docker-compose up` to set a docker containner. 
- You will see an url like this http://localhost:8888/?token=f43925248432eb4cdcd79f12d6192995555137decc1f7bc0
- Browse that url and the email spam implementation is http://localhost:8888/notebooks/data_science_python.ipynb

Data to train the model
- Update the data/SMSSpamCollection if you have a dataset (CSV) for training model.
