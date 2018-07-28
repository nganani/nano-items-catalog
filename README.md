# Item Catalog Web Application
Project for Udacity full stack web developer nanodegree 
## Running the application
* Install dependent libraries using `pip3 install -U -r requirements.txt`
    * Flask
    * sqlalchemy
    * requests
    * oauth2client
* Enter your developer credentials for 3rd party authentication
    * Google:  `client_secrets.json` see [here](https://developers.google.com/maps/documentation/javascript/get-api-key) for more details
    * Facebook: `fb_client_secrets.json`, see [here](https://developers.facebook.com/apps) for more details
* Create empty database: `python3 database_setup.py` 
* Run `python3 app2.py`
Note: This project was written for Python 3 but should work on Python 2 just as well

## License
    Project is released under the [MIT License](http://opensource.org/licenses/MIT).
