requirements

Flask
chatterbot
SQLAlchemy


for training the bot (intents are feeded in yml format)
after training db.sqlite3 will be created and it will be updated for every training

python3 train.py

for running a chatbot in browser (it's a flask app with autostart so we can simply start the app by)

python3 run.py

about confidence level

still this is yet to be implemented hope (confidence > 0.7 is affordable)
