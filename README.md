# Postman
{{base-url}} can be changed by clicking the collection root folder (IBKR) > Pre-request Script:
https://localhost:5000/v1/api - is the base URL for individual account users;
https://api.ibkr.com/v1/api - is the base URL for OAuth users.

When running CP API on Mac computers the default 5000 port is usually ocupied by AirPlay, so another port number should be used instead.
Edit listenPort number in conf.yaml file located in the root folder of CP API installation, port number 5001 should work fine.
Make sure the dase URL contains the same port number.
Please note, this collection uses port number 5001 in base URL.
