# FitPulse
Python-Strava connector that allows you to track personal fitness records and other information

### Get Started
Retrieve your personal client ID and client secret from [strava](https://www.strava.com/settings/api)

### Setup
Setup environment in your folder. Use pip3 freeze to check version
```
python3 -m venv venv
venv\Scripts\activate
pip3 install requests requests-oauthlib python-dotenv
```
Then setup your .env file in the root directory:
```
client_id=YOUR_CLIENT_ID
client_secret=YOUR_CLIENT_SECRET
```


