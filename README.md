# flaskbackend
Flask Backend Server for Hack The North 2018 Alertify Bot that services outpatient care

## Portfolio Devpost Description
More details regarding the high level perspective of the application itself and photos, visit this [link](https://devpost.com/software/alertify-8f3rms)

## Description
Elderly people require much more attention and care, and often, human care givers realisticly cannot provide 24/7 all year support, all the time. When an incident happens at home/somewhere with an elderly person, contacting for help is the highest priority but if there is no one around to do that, risk and health are at stake.
*Therefore, we hacked easily accessible hardware to provide real-time monitoring and alerts of the elderly patient's well being.* This will provide efficient help and communication when no one is around to assist with the casualties or call 911. 


Repo hosts the Flask Python backend server API that acts as an interface for the Fitbit and the Robot to
communicate and exchange information between each other. Posts heartbeat and other info to a Google Firebase database.
The server also hosts the main web application where users can track down video from the robot, medical information with heartbeats, and last seen pictures before the incident happens. 

## Files
* `App.py` is the flask server which uses Firebase, Twilio API 
* `static/` hosts CSS and JS files
* `templates/` hosts the HTML files for our web application frontend
